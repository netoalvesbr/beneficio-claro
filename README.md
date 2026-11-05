# Benefício Claro

Triagem previdenciária em linguagem simples para quem tem dúvidas sobre benefícios do INSS.

> Projeto Integrador – Engenharia de Software (Gran Faculdade) · Fase 3

## O problema

Muitas pessoas deixam de requerer benefícios previdenciários (aposentadoria, auxílio por incapacidade, salário-maternidade, BPC) por não entenderem os requisitos, não saberem quais documentos reunir ou receberem informações desencontradas. Isso atinge principalmente trabalhadores de baixa renda, autônomos, trabalhadores rurais e idosos.

## A solução

Uma aplicação web, gratuita e sem cadastro, que:

1. Faz perguntas simples (idade, sexo, tempo de contribuição, situação de vida);
2. Indica quais benefícios podem se aplicar e quais requisitos já foram atendidos;
3. Lista os documentos úteis para cada pedido;
4. Orienta a procurar o INSS ou um profissional quando o caso for complexo.

## Público beneficiado

- Segurados de baixa renda e com pouco acesso a orientação jurídica
- Autônomos, facultativos e trabalhadores rurais
- Idosos e pessoas com deficiência (BPC/LOAS)
- Escritórios e projetos de assistência jurídica gratuita, como apoio de pré-atendimento

## Tecnologias

- HTML, CSS e JavaScript puro (protótipo sem dependências, roda offline)
- Planejado: React/TypeScript, hospedagem estática (GitHub Pages), testes automatizados das regras

## Como executar

```bash
git clone https://github.com/netoalvesbr/beneficio-claro.git
cd beneficio-claro/prototipo
# abra o index.html no navegador
```

## Estrutura

```
beneficio-claro/
├── README.md
├── docs/relatorio.pdf
└── prototipo/index.html
```

## Roadmap

- [x] Protótipo de triagem (idade, carência, BPC, incapacidade, maternidade)
- [ ] Regras de transição da EC 103/2019
- [ ] Simulação de tempo de contribuição a partir do CNIS
- [ ] Testes automatizados das regras
- [ ] Acessibilidade (WCAG) e versão para celular
- [ ] Validação das regras por profissional da área previdenciária

## Aviso

Ferramenta educativa e simplificada. Não substitui análise jurídica nem a decisão do INSS. Não coleta nem armazena dados pessoais (tudo é processado no navegador), em linha com a LGPD.

## Licença

MIT
