# 3d-print-gcode-extractor
Interface gráfica para exibir e exportar informações técnicas de arquivos G-Code.

# **Extrator de Dados de G-Code**
Ferramenta desenvolvida em Python para a comunidade maker, focada na extração e exportação de dados técnicos de arquivos G-Code de impressão 3D. Com uma interface gráfica intuitiva, é possível visualizar as informações do arquivo e exportá-las para Excel com formatação personalizada.

---

## **Recursos**
- Extração de dados técnicos, como:
  - Tipo de filamento.
  - Densidade e diâmetro do filamento.
  - Altura da camada e número total de camadas.
  - Altura máxima (Z), volume e diâmetro do bico.
  - Tempo estimado de impressão (formato `[h]:mm:ss`).
- Interface gráfica amigável desenvolvida com Tkinter.
- Exportação para Excel com:
  - Formatação personalizada (bordas, títulos em negrito, valores centralizados).
  - Largura ajustada das colunas.
  - Nome do arquivo Excel baseado no nome do G-Code original.

---

## **Pré-requisitos**
Certifique-se de ter o Python instalado no seu computador. Além disso, as bibliotecas abaixo devem estar instaladas:
- **tkinter** (interface gráfica)
- **xlsxwriter** (geração de arquivos Excel)

Para instalar as dependências, execute:
```bash
pip install xlsxwriter
```

---

## **Como Usar**
1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/extrator-gcode.git
   cd extrator-gcode
   ```

2. Execute o script:
   ```bash
   python extrator_gcode.py
   ```

3. Use a interface gráfica para:
   - Selecionar um arquivo G-Code.
   - Visualizar os dados técnicos extraídos.
   - Exportar os dados para um arquivo Excel.

4. O Excel será gerado com o mesmo nome do arquivo G-Code.

---

## **Exemplo de Uso**
### Interface Gráfica
A interface permite:
- Selecionar o arquivo G-Code.
- Visualizar os dados extraídos, como mostrado abaixo:

![Exemplo de Interface](https://via.placeholder.com/800x400.png?text=Interface+Gráfica)

### Excel Gerado
O arquivo Excel possui colunas formatadas e os dados organizados de forma clara:

| Campo                      | Valor       |
|----------------------------|-------------|
| Tipo de Filamento          | PLA         |
| Densidade do Filamento     | 1,24 g/cm³  |
| Diâmetro do Filamento      | 1,75 mm     |
| ...                        | ...         |

---

## **Licença**
Este projeto está licenciado sob a **MIT License** - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## **Contribuições**
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests para melhorias ou novos recursos.

---

## **Contato**
- **Criador**: Geraldo José Fernandes(https://github.com/dmakerlabs)
- **E-mail**: dmakerlabs@gmail.com
