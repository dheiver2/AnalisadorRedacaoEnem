# Analisador de Redações do ENEM

Este projeto é uma aplicação Python que utiliza a API do Gradio para fornecer feedback automatizado sobre redações, focando especificamente nas redações do ENEM. A ferramenta oferece várias opções de análise de texto, como estrutura, introdução, coesão, estilo de escrita, gramática e estimativa de tempo de leitura, além de permitir comparações com uma redação nota 10. 

## Funcionalidades

1. **Análise da Estrutura da Redação**  
   Avalia a presença e a elaboração dos elementos principais, como introdução, desenvolvimento e conclusão, além da coerência, argumentação e uso adequado da linguagem formal.

2. **Análise da Introdução da Redação**  
   Fornece feedback sobre a introdução, abordando aspectos como contextualização, clareza, e recursos para atrair o leitor.

3. **Análise da Coesão do Texto**  
   Verifica a sequência lógica das ideias, o uso de recursos coesivos, a transição entre parágrafos e a manutenção da unidade temática.

4. **Resumo da Redação**  
   Gera um resumo conciso da redação, destacando os principais pontos.

5. **Verificação de Erros Gramaticais**  
   Identifica erros gramaticais e de ortografia no texto.

6. **Análise do Estilo de Escrita**  
   Avalia a fluidez e adequação do estilo de escrita em relação ao tema.

7. **Comparação com uma Redação Nota 10**  
   Compara a redação do usuário com uma redação nota 10 fornecida, destacando as principais diferenças.

8. **Estimativa do Tempo de Leitura**  
   Calcula o tempo médio estimado para leitura com base na contagem de palavras.

## Instalação

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu_usuario/analisador-redacao-enem.git
   ```
2. Instale os pacotes necessários:
   ```bash
   pip install gradio_client
   ```

## Uso

1. Execute o arquivo principal:
   ```bash
   python nome_do_arquivo.py
   ```
2. Escolha uma das opções de análise quando o menu for exibido.

## Exemplo de Uso

Ao executar o programa, você verá o seguinte menu:

```
=== Bem-vindo ao Analisador de Redações do ENEM ===

Selecione o tipo de análise que deseja realizar:
1. Análise da Estrutura da Redação
2. Análise da Introdução da Redação
3. Análise da Coesão do Texto
4. Resumir a Redação
5. Verificação de Erros Gramaticais
6. Análise do Estilo de Escrita
7. Comparar com uma Redação Nota 10
8. Estimar o Tempo de Leitura
9. Sair
```

Escolha o número correspondente à análise desejada e siga as instruções.

## Estrutura do Código

A classe `AnalisadorRedacaoEnem` contém métodos para cada tipo de análise, que enviam prompts para a API do Gradio e recebem feedback detalhado sobre a redação fornecida.

### Métodos Principais

- `analisar_estrutura()`
- `analisar_introducao()`
- `analisar_coesao()`
- `resumir_redacao()`
- `verificar_gramatica()`
- `analisar_estilo()`
- `comparar_com_modelo()`
- `estimar_tempo_leitura()`

### Exemplo de Redação de Entrada

A redação de exemplo discutida no código trata da importância do voto consciente nas eleições de 2024. Este texto pode ser substituído pelo usuário conforme desejado.

## Requisitos

- Python 3.x
- [Gradio Client](https://www.gradio.app)

## Contribuição

Contribuições são bem-vindas! Por favor, abra uma issue ou faça um pull request.

## Licença

Este projeto está licenciado sob a Licença MIT - consulte o arquivo [LICENSE](LICENSE) para mais detalhes.

---

**Autor:**  
Desenvolvido por Dr Dheiver Francisco Santos.
