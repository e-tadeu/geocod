
# Geocod

Bem-vindo ao **Geocod**, um plugin desenvolvido para QGIS que geocodifica endereços constantes em arquivo CSV e gera uma camada de vetores de pontos.

---

## **Instalação do Plugin no QGIS**

Após configurar o ambiente, siga estas etapas para instalar o plugin no QGIS:

1. Baixe ou clone o repositório do plugin em arquivo ZIP.
2. Abra o QGIS.
3. Vá até **Complementos > Gerenciar e Instalar Complementos**.
4. Clique na aba **Instalar de um arquivo ZIP**.
5. Selecione o arquivo ZIP do plugin ou a pasta onde os arquivos foram extraídos.
6. Clique em **Instalar Complemento**.

---

Com essas etapas concluídas, o plugin estará pronto para uso!

---

## **Orientações de uso**

### **Formato do arquivo CSV**

Para o correto funcionamento do plugin, o arquivo CSV de entrada deve:

1. Usar **vírgulas** como separador de colunas.  
2. Conter uma coluna de endereços no formato padronizado, conforme orientação abaixo.

### **Formato da coluna de endereços**

Durante a execução do plugin, você será solicitado a selecionar a **coluna de endereços**. Esta coluna deve conter os endereços formatados no seguinte padrão:

```
"Rua Saladino de Castro, 1575 - Centro, Arapoti, Paraná"
```

**Exemplo de conteúdo CSV:**

```csv
Locais, endereços, obs
Local 1, "Rua Bolívia, 151 - Vila Nova, Barbosa Ferraz, Paraná", Hospital 1
Local 2, "Rua Curitiba, 165 - Jardim América, Assis Chateaubriand, Paraná", Hospital 2
Local 3, "Avenida Thiago Peixoto, 274 - Batel, Antonina, Paraná", Hospital 3
```
---
## Créditos

Este plugin utiliza e adapta código da biblioteca [geocoder](https://github.com/DenisCarriere/geocoder) de Denis Carriere, licenciada sob MIT License.

Agradecemos aos autores originais pelo trabalho e pela disponibilização do código.

## Licença

Este plugin é licenciado sob os termos da licença MIT.

## Autor

**Edson Tadeu da Silva Pinto**

Engenheiro Cartógrafo | Capitão do Exército Brasileiro

Desenvolvido no âmbito de estudos e aplicações em geotecnologias.

+ &copy;2025 Edson Tadeu da Silva Pinto