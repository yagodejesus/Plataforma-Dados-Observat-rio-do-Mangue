# Módulo de FAQ Inteligente

## Visão Geral

O módulo de FAQ inteligente foi implementado utilizando a abordagem Retrieval-Augmented Generation (RAG), permitindo respostas fundamentadas em bases documentais validadas.

## Arquitetura

1. Ingestão de documentos
2. Segmentação (chunking)
3. Geração de embeddings
4. Indexação vetorial
5. Recuperação semântica
6. Geração de resposta via LLM

## Pipeline Técnico

Entrada do usuário → Embedding → Busca vetorial → Recuperação de contexto → Prompt estruturado → Resposta gerada

## Benefícios

- Redução de alucinação
- Respostas fundamentadas
- Escalabilidade
- Atualização dinâmica da base de conhecimento

## Aplicação no Projeto

Utilizado para responder perguntas relacionadas à:
- Sociobiodiversidade
- Protocolos de coleta
- Uso da plataforma
- Governança de dados
