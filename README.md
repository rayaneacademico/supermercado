arttemism ocultismo 


<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Arttemism Ocultismo</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Pirata+One&family=IM+Fell+English:ital@0;1&display=swap" rel="stylesheet">
<script src="https://cdn.jsdelivr.net/npm/@supabase/supabase-js@2"></script>
<style>
:root{
  --preto:#000;
  --preto2:#0a0508;
  --roxo:#7b2fbf;
  --roxo-claro:#c79bef;
  --roxo-fundo:#140a1e;
  --laranja:#ff8a1f;
  --texto:#e9dff5;
  --apagado:#8d7a9e;
}
*{box-sizing:border-box;margin:0;padding:0}
html{background:var(--preto)}
body{
  background:var(--preto);color:var(--texto);
  font-family:"IM Fell English",Georgia,serif;font-size:1.1rem;line-height:1.6;
  min-height:100vh;
}
:focus-visible{outline:2px solid var(--laranja);outline-offset:3px}
.pagina{max-width:1080px;margin:0 auto;padding:0 20px 90px}

/* Laço de renda decorativo, usado como divisor */
.laco{text-align:center;font-size:1.4rem;color:var(--roxo-claro);letter-spacing:.5em;opacity:.8;user-select:none}

header{text-align:center;padding:54px 0 30px;border-bottom:1px solid #2a1533}
.coelho{font-size:3.2rem;display:block;margin-bottom:6px;filter:drop-shadow(0 0 14px rgba(123,47,191,.6))}
h1{
  font-family:"Pirata One","Old English Text MT",serif;font-weight:400;
  font-size:clamp(2.6rem,9vw,5rem);line-height:1;letter-spacing:.02em;
  color:var(--roxo-claro);text-shadow:0 0 26px rgba(123,47,191,.55),2px 2px 0 #000;
}
.lema{margin:16px auto 0;max-width:34em;color:var(--apagado);font-style:italic}
.lema .emote{filter:none;opacity:1}

.ferramentas{display:flex;flex-wrap:wrap;gap:14px;align-items:center;margin:32px 0 8px}
.busca{
  flex:1 1 240px;background:var(--preto2);border:1px solid #2a1533;color:var(--texto);
  font:inherit;padding:10px 14px;border-radius:2px;
}
.busca::placeholder{color:var(--apagado)}
.abas{display:flex;flex-wrap:wrap;gap:8px}
.aba{
  background:var(--preto2);border:1px solid #2a1533;color:var(--roxo-claro);
  font:inherit;padding:8px 14px;cursor:pointer;border-radius:2px;
  transition:background .2s,color .2s,border-color .2s;
}
.aba:hover{background:var(--roxo-fundo)}
.aba[aria-pressed="true"]{background:var(--roxo);border-color:var(--roxo);color:#fff}
.status{color:var(--apagado);font-style:italic;min-height:1.6em;margin-bottom:6px}

section{margin-top:40px}
section h2{
  font-family:"Pirata One",serif;font-weight:400;font-size:1.9rem;
  color:var(--roxo-claro);display:flex;align-items:baseline;gap:12px;flex-wrap:wrap;
}
section h2 .icone{font-size:1.3rem}
section h2 small{font-family:"IM Fell English",serif;font-size:1rem;color:var(--apagado);font-style:italic}
.grade{display:grid;gap:16px;margin-top:16px;grid-template-columns:repeat(auto-fill,minmax(250px,1fr))}

.item{
  position:relative;
  background:var(--preto2);border:1px solid #2a1533;border-left:3px solid var(--roxo);
  padding:16px 18px 16px 20px;display:flex;flex-direction:column;gap:6px;
}
.item::before{
  content:"🎀";position:absolute;top:-11px;right:12px;font-size:1.1rem;
}
.item h3{font-family:"Pirata One",serif;font-weight:400;font-size:1.4rem;line-height:1.15}
.desc{color:var(--apagado);font-size:.97rem}
.preco{font-family:"Pirata One",serif;font-size:1.7rem;color:var(--roxo-claro);margin-top:auto}
.dados{display:grid;grid-template-columns:auto 1fr;gap:2px 12px;font-size:.94rem}
.dados dt{color:var(--apagado)}
.selo{display:inline-block;padding:2px 10px;border:1px solid;font-size:.88rem;width:fit-content}
.selo.ok{color:var(--roxo-claro);border-color:var(--roxo)}
.selo.alerta{color:var(--laranja);border-color:var(--laranja)}
.selo.morto{color:#ff5d5d;border-color:#ff5d5d;text-decoration:line-through wavy}
.vazio{padding:40px 0;text-align:center;color:var(--apagado);font-style:italic}

footer{margin-top:70px;padding-top:22px;border-top:1px solid #2a1533;text-align:center;color:var(--apagado);font-size:.94rem}
footer .bichinhos{display:block;margin-top:8px;font-size:1.3rem;letter-spacing:.3em}

@media (prefers-reduced-motion:no-preference){
  .coelho{animation:flutuar 4s ease-in-out infinite}
  @keyframes flutuar{50%{transform:translateY(-6px)}}
}
</style>
</head>
<body>
<div class="pagina">
  <header>
    <span class="coelho" aria-hidden="true">🐇🖤</span>
    <h1>Arttemism Ocultismo</h1>
    <p class="lema">Catálogo de itens para rituais, altares e magias domésticas <span class="emote">🕯️🎀🐇</span></p>
  </header>

  <p class="laco" aria-hidden="true">﹉ ﹉ ﹉ ﹉ ﹉</p>

  <div class="ferramentas">
    <input class="busca" id="busca" type="search" placeholder="Buscar item..." aria-label="Buscar item">
    <div class="abas" id="abas"></div>
  </div>
  <p class="status" id="status" role="status">Acendendo as velas...</p>

  <main id="lista"></main>

  <p class="laco" aria-hidden="true">﹉ ﹉ ﹉ ﹉ ﹉</p>

  <footer>
    Arttemism Ocultismo, projeto de Banco de Dados.
    <span class="bichinhos" aria-hidden="true">🖤 🎀 🐇 🎀 🖤</span>
  </footer>
</div>

<script>
// ============ CONFIGURAÇÃO DO SUPABASE ============
// Pegue a chave em: Project Settings > API > "anon public"
const SUPABASE_URL = "https://btqsubtnvlztypbbqqtf.supabase.co";
const SUPABASE_KEY = "COLE_AQUI_SUA_ANON_KEY";
const TABELA = "arttemism_ocultismo";
// ==================================================

const CATEGORIAS = [
  {id:"vela",           nome:"Velas e Chamas",        icone:"🕯️"},
  {id:"incenso",        nome:"Incensos e Fumaças",    icone:"🌫️"},
  {id:"oleo_essencial", nome:"Óleos Essenciais",      icone:"🧴"},
  {id:"cristal",        nome:"Cristais e Pedras",     icone:"🔮"},
  {id:"erva",           nome:"Ervas e Defumação",     icone:"🌿"},
  {id:"tarot",          nome:"Tarot e Oráculos",      icone:"🎴"},
  {id:"outros",         nome:"Relíquias Diversas",    icone:"🖤"}
];

// Dados de exemplo, usados se a chave ainda não foi colocada
const DEMO = [
  {id:1,produto:"Vela Preta de Proteção",categoria:"vela",descricao:"Cera vegetal, ritual de banimento",peso:0.12,valor:14.9,quantidade_estoque:80,data_de_fabricacao:"2026-08-01",data_de_validade:null,fornecedor:"Ateliê Lunar",lote:"V001"},
  {id:2,produto:"Vela Roxa de Intuição",categoria:"vela",descricao:"Aromática de lavanda",peso:0.12,valor:15.9,quantidade_estoque:65,data_de_fabricacao:"2026-08-01",data_de_validade:null,fornecedor:"Ateliê Lunar",lote:"V002"},
  {id:3,produto:"Incenso de Sândalo",categoria:"incenso",descricao:"Caixa com 20 varetas",peso:0.05,valor:9.9,quantidade_estoque:150,data_de_fabricacao:"2026-07-15",data_de_validade:"2028-07-15",fornecedor:"Fumaça Sagrada",lote:"I001"},
  {id:4,produto:"Óleo Essencial de Lavanda",categoria:"oleo_essencial",descricao:"Frasco conta-gotas, 10ml",ml:10,valor:29.9,quantidade_estoque:45,data_de_fabricacao:"2026-06-10",data_de_validade:"2028-06-10",fornecedor:"Botica das Ervas",lote:"O001"},
  {id:5,produto:"Cristal Ametista Bruta",categoria:"cristal",descricao:"Pedra bruta para meditação",peso:0.08,valor:24,quantidade_estoque:30,data_de_fabricacao:null,data_de_validade:null,fornecedor:"Pedras da Lua",lote:"E001"},
  {id:6,produto:"Sálvia Branca para Defumação",categoria:"erva",descricao:"Maço de ervas secas",peso:0.03,valor:18,quantidade_estoque:55,data_de_fabricacao:"2026-05-01",data_de_validade:"2027-05-01",fornecedor:"Botica das Ervas",lote:"E002"},
  {id:7,produto:"Baralho de Tarot Rider-Waite",categoria:"tarot",descricao:"78 cartas com manual",peso:0.3,valor:69.9,quantidade_estoque:20,data_de_fabricacao:null,data_de_validade:null,fornecedor:"Oráculo & Cia",lote:"T001"}
];

let produtos = [];
let categoriaAtual = "todas";

const $ = s => document.querySelector(s);
const esc = t => String(t ?? "").replace(/[&<>"']/g, c => ({"&":"&amp;","<":"&lt;",">":"&gt;",'"':"&quot;","'":"&#39;"}[c]));
const dinheiro = v => Number(v).toLocaleString("pt-BR",{style:"currency",currency:"BRL"});
const num = v => Number(v).toLocaleString("pt-BR",{maximumFractionDigits:3});
const dataBR = d => d ? new Date(d + "T00:00:00").toLocaleDateString("pt-BR") : "sem data";

function medida(p){
  const partes = [];
  if (p.peso != null)   partes.push(num(p.peso) + " kg");
  if (p.litro != null)  partes.push(num(p.litro) + " L");
  else if (p.ml != null) partes.push(num(p.ml) + " ml");
  else if (p.volume != null) partes.push(num(p.volume) + " de volume");
  return partes.join(" / ") || "não informada";
}

function selo(p){
  if (!p.data_de_validade) return `<span class="selo ok">Sem validade</span>`;
  const hoje = new Date(); hoje.setHours(0,0,0,0);
  const dias = Math.round((new Date(p.data_de_validade + "T00:00:00") - hoje) / 86400000);
  if (dias < 0)  return `<span class="selo morto">Vencido, amaldiçoado</span>`;
  if (dias <= 7) return `<span class="selo alerta">Vence em ${dias} dia${dias === 1 ? "" : "s"}</span>`;
  return `<span class="selo ok">Válido até ${dataBR(p.data_de_validade)}</span>`;
}

function cartao(p){
  return `<article class="item">
    <h3>${esc(p.produto)}</h3>
    ${p.descricao ? `<p class="desc">${esc(p.descricao)}</p>` : ""}
    ${selo(p)}
    <dl class="dados">
      <dt>Medida</dt><dd>${esc(medida(p))}</dd>
      <dt>Estoque</dt><dd>${esc(p.quantidade_estoque ?? 0)} un.</dd>
      ${p.fornecedor ? `<dt>Fornecedor</dt><dd>${esc(p.fornecedor)}</dd>` : ""}
      ${p.lote ? `<dt>Lote</dt><dd>${esc(p.lote)}</dd>` : ""}
    </dl>
    <p class="preco">${dinheiro(p.valor)}</p>
  </article>`;
}

function desenhar(){
  const termo = $("#busca").value.trim().toLowerCase();
  const filtrados = produtos.filter(p =>
    (categoriaAtual === "todas" || p.categoria === categoriaAtual) &&
    (!termo || (p.produto || "").toLowerCase().includes(termo))
  );

  let html = "";
  CATEGORIAS.forEach(c => {
    const grupo = filtrados.filter(p => p.categoria === c.id);
    if (!grupo.length) return;
    html += `<section>
      <h2><span class="icone">${c.icone}</span>${c.nome} <small>${grupo.length} ${grupo.length === 1 ? "item" : "itens"}</small></h2>
      <div class="grade">${grupo.map(cartao).join("")}</div>
    </section>`;
  });
  $("#lista").innerHTML = html || `<p class="vazio">Nenhum item respondeu ao chamado 🐇🖤. Tente outro nome ou outra aba.</p>`;
}

function montarAbas(){
  const abas = [{id:"todas", nome:"Tudo", icone:"🎀"}, ...CATEGORIAS];
  $("#abas").innerHTML = abas.map(a =>
    `<button class="aba" data-cat="${a.id}" aria-pressed="${a.id === categoriaAtual}">${a.icone} ${a.nome}</button>`).join("");
  document.querySelectorAll(".aba").forEach(b => b.addEventListener("click", () => {
    categoriaAtual = b.dataset.cat;
    document.querySelectorAll(".aba").forEach(x => x.setAttribute("aria-pressed", x === b));
    desenhar();
  }));
}

async function carregar(){
  montarAbas();
  $("#busca").addEventListener("input", desenhar);

  if (SUPABASE_KEY.startsWith("COLE_AQUI")) {
    produtos = DEMO;
    $("#status").textContent = "Modo demonstração: cole sua anon key no script para ler o estoque real do Supabase.";
    return desenhar();
  }
  try {
    const db = supabase.createClient(SUPABASE_URL, SUPABASE_KEY);
    const { data, error } = await db.from(TABELA).select("*");
    if (error) throw error;
    produtos = data || [];
    $("#status").textContent = `${produtos.length} itens no catálogo.`;
  } catch (e) {
    console.error(e);
    produtos = DEMO;
    $("#status").textContent = "O feitiço falhou ao falar com o Supabase (veja o console, F12). Mostrando dados de exemplo.";
  }
  desenhar();
}
carregar();
</script>
</body>
</html>
