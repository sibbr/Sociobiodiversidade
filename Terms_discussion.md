# Discussão dos termos 

## Como discutir um termo

Para iniciar uma discussão sobre algum termo, clique no título das tabelas abaixo. Assim, você será direcionado para a página específica de discussão do termo escolhido.
Para cada termo apresentado:
- **Identificador:** acesso a descrição original do site oficial do Darwin Core (TDWG).
- **Definição:** enunciado que explica o significado de um termo.
- **Domínio:** termo obrigatório exatamente como deveria estar escrito.
- **Exemplos:** vários exemplos segundo o tipo de dados e/ou grupo taxonômico.

#### usedTo

<table>
  <tr class="table-secondary">
    <th colspan="2">
      <a href="https://github.com/sibbr/DarwinCoreBrasil/issues/1" target="_blank" rel="noopener noreferrer"
        >usedTo</a
      >
    </th>
  </tr>
  <tr>
    <td style="text-align: left">Identificador</td>
    <td style="text-align: left">
      <a href="https://dwc.tdwg.org/terms/#dwc:datasetName"
        >https://dwc.tdwg.org/terms/#dwc:datasetName</a
      >
    </td>
  </tr>
  <tbody>
    <tr>
      <td style="text-align: left">Definição</td>
      <td style="text-align: left">
       Refere-se à finalidade ou propósito de uso do táxon (uso passado, atual ou contínuo).
      </td>
    </tr>
    <tr>
      <td style="text-align: left">Domínio</td>
      <td style="text-align: left">[Finalidade de uso do táxon]</td>
    </tr>
    <tr>
      <td style="text-align: left">Exemplos</td>
      <td style="text-align: left">
        <ul>
          <li>
            Coleções de Zoologia:
            <a
              href="https://collectory.sibbr.gov.br/collectory/public/show/dr797"
              >Coleção de Mamíferos do Museu Nacional da UFRJ</a
          </li>
          <li>
            Herbários:
            <a
              href="https://collectory.sibbr.gov.br/collectory/public/show/dr839"
              >Rio de Janeiro Botanical Garden Herbarium Collection</a
          </li>
          <li>
            Subcoleções: <a href="https://collectory.sibbr.gov.br/collectory/public/showDataResource/dr895">Coleção Entomológica do MNRJ - Odonata</a>
          </li>
          <li>
            Programa PELD:
            <a
              href="https://collectory.sibbr.gov.br/collectory/public/show/dr670"
              >PELD - PNCA | Dados da ocorrência de Coleópteros em um gradiente de perturbação/precipitação em área de Caatinga, Parque Nacional do Catimbau, Buíque, PE, Brasil </a
            >
          </li>
          <li>
            Programa PPBio: <a href="https://collectory.sibbr.gov.br/collectory/public/show/dr651">PPBioMA | Morcegos no Parque Nacional da
            Chapada dos Guimarães</a>
          </li>
          <li>
            Projeto de pesquisa:
            <a
              href="https://collectory.sibbr.gov.br/collectory/public/show/dr642"
              >PREVIR | Monitoramento de Fauna do Projeto Rede de Vigilância de Vírus. Observatório Pantanal AVES MT-2</a
            >
          </li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

---
#### usedToRemarks
<table>
  <tr ="table-secondary">
    <th colspan="2">
      <a href="https://github.com/sibbr/DarwinCoreBrasil/issues/2">usedToRemarks</a>
    </th>
  </tr>
  <tr>
    <td style="text-align: left">Identificador</td>
    <td style="text-align: left">
      <a href="https://dwc.tdwg.org/terms/#dc:type"
        >https://dwc.tdwg.org/terms/#dc:type</a
      >
    </td>
  </tr>
  <tbody>
    <tr>
      <td style="text-align: left">Definição</td>
      <td style="text-align: left">Expande a explicação do propósito de uso do táxon, descrevendo o uso de forma mais específica.</td>
    </tr>
    <tr>
      <td style="text-align: left">Domínio</td>
      <td style="text-align: left">
        [Explicação do propósito de uso do táxon]
      </td>
    </tr>
    <tr>
      <td style="text-align: left">Exemplos</td>
      <td style="text-align: left">
        <ul>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

---
#### organismPart
<table>
  <tr ="table-secondary">
    <th colspan="2">
      <a href="https://github.com/sibbr/DarwinCoreBrasil/issues/3">organismPart</a>
    </th>
  </tr>
  <tr>
    <td style="text-align: left">Identificador</td>
    <td style="text-align: left">
      <a href="https://dwc.tdwg.org/terms/#dcterms:modified"
        >https://dwc.tdwg.org/terms/#dcterms:modified</a
      >
    </td>
  </tr>
  <tbody>
    <tr>
      <td style="text-align: left">Definição</td>
      <td style="text-align: left">
        A parte específica do táxon à qual o nome de uso se refere. Se o táxon estiver associado a múltiplos usos, cada parte deve ser documentada em uma linha separada correspondente ao mesmo taxonID.
      </td>
    </tr>
    <tr>
      <td style="text-align: left">Domínio</td>
      <td style="text-align: left">AAAA-MM-DD</td>
    </tr>
    <tr>
      <td style="text-align: left">Exemplos</td>
      <td style="text-align: left">
        <ul>
          <li>2023-07-06</li>
          <li>2022-04-23</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

---
#### organismPartDescription
<table>
  <tr ="table-secondary">
    <th colspan="2">
      <a href="https://github.com/sibbr/DarwinCoreBrasil/issues/4">organismPartDescription</a>
    </th>
  </tr>
  <tr>
    <td style="text-align: left">Identificador</td>
    <td style="text-align: left">
      <a href="https://dwc.tdwg.org/terms/#dc:language"
        >https://dwc.tdwg.org/terms/#dc:language</a
      >
    </td>
  </tr>
  <tbody>
    <tr>
      <td style="text-align: left">Definição</td>
      <td style="text-align: left">A descrição da parte específica do táxon a qual se aplica o uso do táxon.</td>
    </tr>
    <tr>
      <td style="text-align: left">Domínio</td>
      <td style="text-align: left">pt | en | es</td>
    </tr>
    <tr>
      <td style="text-align: left">Exemplos</td>
      <td style="text-align: left">
        <ul>
          <li>pt: Português</li>
          <li>en: Inglês</li>
          <li>es: Espanhol</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

---
#### usedForm
<table>
  <tr ="table-secondary">
    <th colspan="2">
      <a href="https://github.com/sibbr/DarwinCoreBrasil/issues/5">usedForm</a>
    </th>
  </tr>
  <tr>
    <td style="text-align: left">Identificador</td>
    <td style="text-align: left">
      <a href="https://dwc.tdwg.org/terms/#dcterms:license"
        >https://dwc.tdwg.org/terms/#dcterms:license</a
      >
    </td>
  </tr>
  <tbody>
    <tr>
      <td style="text-align: left">Definição</td>
      <td style="text-align: left">
        A forma como a parte específica do táxon é utilizada, sua preparação ou método de aplicação. Se a mesma parte estiver associada a múltiplos usos, cada forma de uso deve ser documentada em uma linha separada correspondente ao mesmo taxonID e organismPart.
      </td>
    </tr>
    <tr>
      <td style="text-align: left">Domínio</td>
      <td style="text-align: left">CC0 | CC BY | CC BY - NC</td>
    </tr>
    <tr>
      <td style="text-align: left">Exemplos</td>
      <td style="text-align: left">
        <ul>
          <li>
            <a href="https://sibbr.gov.br/page/termo-de-uso-de-dados.html"
              >Termo de uso SiBBr</a
            >
          </li>
          <li>
            <a href="https://sibbr.gov.br/page/licenca-uso.html">Licença CC0</a>
          </li>
          <li>
            <a href="https://sibbr.gov.br/page/licenca-uso.html"
              >Licença CC BY</a
            >
          </li>
          <li>
            <a href="https://sibbr.gov.br/page/licenca-uso.html"
              >Licença CC BY - NC</a
            >
          </li>
          <li><a href="https://www.gbif.org/pt/terms">Creative Commons</a></li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

---
#### usedFormDescription
<table>
  <tr ="table-secondary">
    <th colspan="2">
      <a href="https://github.com/sibbr/DarwinCoreBrasil/issues/6"
        >usedFormDescription</a
      >
    </th>
  </tr>
  <tr>
    <td style="text-align: left">Identificador</td>
    <td style="text-align: left">
      <a href="https://dwc.tdwg.org/terms/#dcterms:rightsHolder"
        >https://dwc.tdwg.org/terms/#dcterms:rightsHolder</a
      >
    </td>
  </tr>
  <tbody>
    <tr>
      <td style="text-align: left">Definição</td>
      <td style="text-align: left">
        Descrição detalhada da forma de uso da parte específica do táxon, incluindo etapas de preparação, dosagem, frequência, modo de aplicação e quaisquer variações culturais ou regionais relevantes. Esta descrição pode expandir a informação registrada em usedForm.
      </td>
    </tr>
    <tr>
      <td style="text-align: left">Domínio</td>
      <td style="text-align: left">
        [Nome completo do pesquisador ou instituição]
      </td>
    </tr>
    <tr>
      <td style="text-align: left">Exemplos</td>
      <td style="text-align: left">
        Para coleções:
        <ul>
        <li>
        Universidade do Vale do Taquari
        </li>
        <li>
        Museu de Pesquisas da Amazônia
        </li>
        </ul>
        Para projetos de pesquisa:
        <ul>
        <li>
        Nome do pesquisador
        </li>
        <li>
        Instituto Brasileiro do Meio Ambiente e dos Recursos Naturais
        </li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

---
#### usedByHolder
<table>
  <tr ="table-secondary">
    <th colspan="2">
      <a href="https://github.com/sibbr/DarwinCoreBrasil/issues/7"
        >usedByHolder</a
      >
    </th>
  </tr>
  <tr>
    <td style="text-align: left">Identificador</td>
    <td style="text-align: left">
      <a href="https://dwc.tdwg.org/terms/#dcterms:accessRights"
        >https://dwc.tdwg.org/terms/#dcterms:accessRights</a
      >
    </td>
  </tr>
  <tbody>
    <tr>
      <td style="text-align: left">Definição</td>
      <td style="text-align: left">
        Identifica a comunidade, grupo, instituição ou entidade que detém o conhecimento tradicional associado ao táxon e que pode ou não utilizar o recurso biológico ou o benefício derivado.
      </td>
    </tr>
    <tr>
      <td style="text-align: left">Domínio</td>
      <td style="text-align: left">
        [Link de acesso]
      </td>
    </tr>
    <tr>
      <td style="text-align: left">Exemplos</td>
      <td style="text-align: left">
        <ul>
          <li>
            <a
              href="https://cidacs.bahia.fiocruz.br/plataformazika/wp-content/uploads/2022/04/POLITICA-DE-DADO-DA-FIOCRUZ.pdf"
              >Política de dados Fiocruz</a
            >
          </li>
          <li>
            <a
              href="https://ppbio.inpa.gov.br/sites/default/files/politica_dou.pdf"
              >Política de dados PPBio</a
            >
          </li>
          <li>
            <a
              href="https://dspace.jbrj.gov.br/jspui/bitstream/doc/125/1/Plano_de_Dados_Abertos_JBRJ_2021_2022_Versao_1.1.pdf"
              > Política de dados JBRJ</a
            >
          </li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

---
#### usedByType
<table>
  <tr ="table-secondary">
    <th colspan="2">
      <a href="https://github.com/sibbr/DarwinCoreBrasil/issues/8"
        >usedByType</a
      >
    </th>
  </tr>
  <tr>
    <td style="text-align: left">Identificador</td>
    <td style="text-align: left">
      <a href="https://dwc.tdwg.org/terms/#dcterms:bibliographicCitation"
        >https://dwc.tdwg.org/terms/#dcterms:bibliographicCitation</a
      >
    </td>
  </tr>
  <tbody>
    <tr>
      <td style="text-align: left">Definição</td>
      <td style="text-align: left">
        A categoria ou segmento da comunidade, grupo ou organização que faz uso do táxon para um ou mais propósitos.
      </td>
    </tr>
    <tr>
      <td style="text-align: left">Domínio</td>
      <td style="text-align: left">[Referência bibliográfica]</td>
    </tr>
    <tr>
      <td style="text-align: left">Exemplos</td>
      <td style="text-align: left">
        <ul>
        <li>
          Rand, K.M., Logerwell, E.A. The first demersal trawl survey of benthic fish and invertebrates in the Beaufort Sea since the late 1970s. Polar Biol 34, 475–488 (2011). https://doi.org/10.1007/s00300-010-0900-2 
        </li>
          <li>
            <a
              href= "https://ala-hub.sibbr.gov.br/ala-hub/occurrences/02712d2c-69c6-4a4b-899f-da3cf945922c"
              >http://www.tropicos.org/Specimen/3184430</a>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

---
#### usedByDescription
<table>
  <tr ="table-secondary">
    <th colspan="2">
      <a href="https://github.com/sibbr/DarwinCoreBrasil/issues/9"
        >usedByDescription</a
      >
    </th>
  </tr>
  <tr>
    <td style="text-align: left">Identificador</td>
    <td style="text-align: left">
      <a href="https://dwc.tdwg.org/terms/#dcterms:references"
        >https://dwc.tdwg.org/terms/#dcterms:references</a
      >
    </td>
  </tr>
  <tbody>
    <tr>
      <td style="text-align: left">Definição</td>
      <td style="text-align: left">
       Descrição do usuário dentro da comunidade que utiliza o organismo para um ou múltiplos propósitos.
      </td>
    </tr>
    <tr>
      <td style="text-align: left">Domínio</td>
      <td style="text-align: left">[Link de acesso]</td>
    </tr>
    <tr>
      <td style="text-align: left">Exemplos</td>
      <td style="text-align: left">
        Referenciar um táxon:
        <ul>
        <li>
        Flora e Funga do Brasil: <a href="https://floradobrasil.jbrj.gov.br/FB15294">https://floradobrasil.jbrj.gov.br/FB15294</a>
        </li>
        <li>
        Catálogo Taxonômico da Fauna do Brasil: <a href="http://fauna.jbrj.gov.br/fauna/faunadobrasil/40390" >http://fauna.jbrj.gov.br/fauna/faunadobrasil/40390</a >
        </li>
        <li>
        Catalogue of Life (CoL): <a href="https://www.catalogueoflife.org/data/taxon/3DR25"> https://www.catalogueoflife.org/data/taxon/3DR25 </a>
        </li>
        <li>
        WoRMS: <a href="https://www.marinespecies.org/aphia.php?p=taxdetails&id=105847"> https://www.marinespecies.org/aphia.php?p=taxdetails&id=105847 </a>
        </li>
        <li>
        Vírus: <a href="https://www.ncbi.nlm.nih.gov/labs/virus/vssi/#/"> https://www.ncbi.nlm.nih.gov/labs/virus/vssi/#/ </a>
        </li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

---
#### sourceType
<table>
  <tr ="table-secondary">
    <th colspan="2">
      <a href="https://github.com/sibbr/DarwinCoreBrasil/issues/9"
        >sourceType</a
      >
    </th>
  </tr>
  <tr>
    <td style="text-align: left">Identificador</td>
    <td style="text-align: left">
      <a href="https://dwc.tdwg.org/terms/#dwc:feedbackURL"
        >https://dwc.tdwg.org/terms/#dwc:feedbackURL</a
      >
    </td>
  </tr>
  <tbody>
    <tr>
      <td style="text-align: left">Definição</td>
      <td style="text-align: left">
        Refere-se à categoria da fonte por meio da qual obteve-se a informação sobre o táxon.
      </td>
    </tr>
    <tr>
      <td style="text-align: left">Domínio</td>
      <td style="text-align: left">[Link]</td>
    </tr>
    <tr>
       <td style="text-align: left">Exemplos</td>
      <td style="text-align: left">
        <ul>https://example.com/new?title=New+issue&body=This+comment+is+about+CAN12345</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

---
#### sourceDescription
<table>
  <tr ="table-secondary">
    <th colspan="2">
      <a href="https://github.com/sibbr/DarwinCoreBrasil/issues/10"
        >sourceDescription</a
      >
    </th>
  </tr>
  <tr>
    <td style="text-align: left">Identificador</td>
    <td style="text-align: left">
      <a href="https://dwc.tdwg.org/terms/#dwc:institutionID"
        >https://dwc.tdwg.org/terms/#dwc:institutionID</a
      >
    </td>
  </tr>
  <tbody>
    <tr>
      <td style="text-align: left">Definição</td>
      <td style="text-align: left">
        Descrição da fonte por meio da qual se obteve a informação sobre o uso.
      </td>
    </tr>
    <tr>
      <td style="text-align: left">Domínio</td>
      <td style="text-align: left">  </td>
    </tr>
    <tr>
      <td style="text-align: left">Exemplos</td>
      <td style="text-align: left">
        <ul>
        <!-- <li>NA</li> -->
        </ul>
      </td>
    </tr>
  </tbody>
</table>

---
#### usedWhere
<table>
  <tr ="table-secondary">
    <th colspan="2">
      <a href="https://github.com/sibbr/DarwinCoreBrasil/issues/11"
        >usedWhere</a
      >
    </th>
  </tr>
  <tr>
    <td style="text-align: left">Identificador</td>
    <td style="text-align: left">
      <a href="https://dwc.tdwg.org/terms/#dwc:collectionID"
        >https://dwc.tdwg.org/terms/#dwc:collectionID</a
      >
    </td>
  </tr>
  <tbody>
    <tr>
      <td style="text-align: left">Definição</td>
      <td style="text-align: left">
        Refere-se a uma região espacial ou local específico onde o táxon é ou era usado.
      </td>
    </tr>
    <tr>
      <td style="text-align: left">Domínio</td>
      <td style="text-align: left">[Identificador da coleção]</td>
    </tr>
    <tr>
      <td style="text-align: left">Exemplos</td>
      <td style="text-align: left">
        <ul>
          <!-- <li>NA</li> -->
        </ul>
      </td>
    </tr>
  </tbody>
</table>

---
#### temporal | UsedWhen
<table>
  <tr ="table-secondary">
    <th colspan="2">
      <a href="https://github.com/sibbr/DarwinCoreBrasil/issues/12"
        >temporal | UsedWhen</a
      >
    </th>
  </tr>
  <tr>
    <td style="text-align: left">Identificador</td>
    <td style="text-align: left">
      <a href="https://dwc.tdwg.org/terms/#dwc:datasetID"
        >https://dwc.tdwg.org/terms/#dwc:datasetID</a
      >
    </td>
  </tr>
  <tbody>
    <tr>
      <td style="text-align: left">Definição</td>
      <td style="text-align: left">
         Contexto temporal em que o organismo é ou era usado.
      </td>
    </tr>
    <tr>
      <td style="text-align: left">Domínio</td>
      <td style="text-align: left">[Instituição]:[Programa]:[Projeto]</td>
    </tr>
    <tr>
      <td style="text-align: left">Exemplos</td>
      <td style="text-align: left">
        <ul>
          <li>RENOVA:RENOVA:PMBA:P164</li>
          <li>ICMBio:ICMBio:SALVE:37463</li>
          <li>ICMBio:Sisbio:XXXXX</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

---
#### locality
<table>
  <tr ="table-secondary">
    <th colspan="2">
      <a href="https://github.com/sibbr/DarwinCoreBrasil/issues/13"
        >locality</a
      >
    </th>
  </tr>
  <tr>
    <td style="text-align: left">Identificador</td>
    <td style="text-align: left">
      <a href="https://dwc.tdwg.org/terms/#dwc:locality"
        >https://dwc.tdwg.org/terms/#dwc:locality</a
      >
    </td>
  </tr>
  <tbody>
    <tr>
      <td style="text-align: left">Definição</td>
      <td style="text-align: left">
      Descrição específica da área de onde a informação foi coletada.
      </td>
    </tr>
    <tr>
      <td style="text-align: left">Domínio</td>
      <td style="text-align: left">[Acrônimo da instituição]</td>
    </tr>
    <tr>
      <td style="text-align: left">Exemplos</td>
      <td style="text-align: left">
        <ul>
          <li>UFPR</li>
          <li>MZUSP</li>
          <li>EMBRAPA</li>
          <li>INPA</li>
          <li>MPEG</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

---
#### recordedBy
<table>
  <tr ="table-secondary">
    <th colspan="2">
      <a href="https://github.com/sibbr/DarwinCoreBrasil/issues/14"
        >recordedBy</a
      >
    </th>
  </tr>
  <tr>
    <td style="text-align: left">Identificador</td>
    <td style="text-align: left">
      <a href="https://dwc.tdwg.org/terms/#dwc:recordedBy"
        >https://dwc.tdwg.org/terms/#dwc:recordedBy</a
      >
    </td>
  </tr>
  <tbody>
    <tr>
      <td style="text-align: left">Definição</td>
      <td style="text-align: left">
       Identifica a pessoa, pessoas, grupos ou organizações responsáveis por registrar a ocorrência original de uso do táxon.
      </td>
    </tr>
    <tr>
      <td style="text-align: left">Domínio</td>
      <td style="text-align: left">[Sobrenome, Inicial nome]</td>
    </tr>
    <tr>
      <td style="text-align: left">Exemplos</td>
      <td style="text-align: left">
        <ul>
          <li>
              <a
              href="https://ala-hub.sibbr.gov.br/ala-hub/occurrences/86b9fb12-c2b9-4695-ade6-b0b00ba4e0a5"
              >Marquete, R</a
            >
          </li>
          <li>
            <a
              href="https://ala-hub.sibbr.gov.br/ala-hub/occurrences/4cc24396-7858-4bc0-b0d6-5a9849633e72"
              >	Ribeiro, F. Juliana | Vieira, E. Emerson</a
            >
          </li>
          <li>
              <a
              href="https://ala-hub.sibbr.gov.br/ala-hub/occurrences/34c20a2b-f1b3-4db3-adcd-f6fddbf534b1"
              >Zikan, J.F.</a
            <
            </li>
              <li>
                Clara Baringo
              </li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

---
#### eventDate
<table>
  <tr class="table-secondary">
    <th colspan="2">
      <a href="https://github.com/sibbr/DarwinCoreBrasil/issues/55"
        >eventDate</a
      >
    </th>
  </tr>
  <tr>
    <td style="text-align: left">Identificador</td>
    <td style="text-align: left">
      <a href="https://dwc.tdwg.org/terms/#dwc:eventDate"
        >https://dwc.tdwg.org/terms/#dwc:eventDate</a
      >
    </td>
  </tr>
  <tbody>
    <tr>
      <td style="text-align: left">Definição</td>
      <td style="text-align: left">
        A data ou intervalo de datas em que a informação foi documentada, independentemente de quando o fenômeno, prática ou conhecimento associado ocorreu originalmente.
      </td>
    </tr>
    <tr>
      <td style="text-align: left">Domínio</td>
      <td style="text-align: left">AAAA-MM-DD</td>
    </tr>
    <tr>
      <td style="text-align: left">Exemplos</td>
      <td style="text-align: left">
        <ul>
          <li>
            <a
              href ="https://ala-hub.sibbr.gov.br/ala-hub/occurrences/e9c03e9b-1c42-4bc3-97c5-b6eec03867c4"
              >Data com ano: 1890 </a>
          </li>
          <li>
            <a
              href="https://ala-hub.sibbr.gov.br/ala-hub/occurrences/bf050988-7ed3-4768-a699-b351767ca030"
              > Data com ano e mês: 2006-04 </a>
            </li>
          <li>
            <a
              href="https://ala-hub.sibbr.gov.br/ala-hub/occurrences/4da67201-14cb-4e13-8fe0-e891e20abb1f"
            >Data completa: 2022-04-21</a>
          </li>
              </ul>
      </td>
    </tr>
  </tbody>
</table>
---
#### language
<table>
  <tr ="table-secondary">
    <th colspan="2">
      <a href="https://github.com/sibbr/DarwinCoreBrasil/issues/16"
        >language</a
      >
    </th>
  </tr>
  <tr>
    <td style="text-align: left">Identificador</td>
    <td style="text-align: left">
      <a href="https://dwc.tdwg.org/terms/#dwc:language"
        >https://dwc.tdwg.org/terms/#dwc:language</a
      >
    </td>
  </tr>
  <tbody>
    <tr>
      <td style="text-align: left">Definição</td>
      <td style="text-align: left">
        Idioma em que está registrada a informação.
      </td>
    </tr>
    <tr>
      <td style="text-align: left">Domínio</td>
      <td style="text-align: left">
        pt | en | es
      </td>
    </tr>
    <tr>
      <td style="text-align: left">Exemplos</td>
      <td style="text-align: left">
        <ul>
          <li>pt: Português
          <li>en: Inglês </li>
          <li>
            es: Espanhol
          </li>
          </ul>
      </td>
    </tr>
  </tbody>
</table>

---
#### references
<table>
  <tr ="table-secondary">
    <th colspan="2">
      <a href="https://github.com/sibbr/DarwinCoreBrasil/issues/17"
        >references</a
      >
    </th>
  </tr>
  <tr>
    <td style="text-align: left">Identificador</td>
    <td style="text-align: left">
      <a href="https://dwc.tdwg.org/terms/#dwc:references"
        >https://dwc.tdwg.org/terms/#dwc:references</a
      >
    </td>
  </tr>
  <tbody>
    <tr>
      <td style="text-align: left">Definição</td>
      <td style="text-align: left">
        Um recurso relacionado ao uso do táxon que é referenciado, citado ou indicado na informação coletada.
      </td>
    </tr>
    <tr>
      <td style="text-align: left">Domínio</td>
      <td style="text-align: left"> [Informações não compartilhadas]
      </td>
    </tr>
    <tr>
      <td style="text-align: left">Exemplos</td>
      <td style="text-align: left">
        <ul>
          <li>Localização não disponibilizada para espécies ameaçadas.</li>
          <li>Informações pessoais do identificador.</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

---
#### associatedMedia
<table>
  <tr ="table-secondary">
    <th colspan="2">
      <a href="https://github.com/sibbr/DarwinCoreBrasil/issues/18"
        >associatedMedia</a
      >
    </th>
  </tr>
  <tr>
    <td style="text-align: left">Identificador</td>
    <td style="text-align: left">
      <a href="https://dwc.tdwg.org/terms/#dwc:associatedMedia"
        >https://dwc.tdwg.org/terms/#dwc:associatedMedia</a
      >
    </td>
  </tr>
  <tbody>
    <tr>
      <td style="text-align: left">Definição</td>
      <td style="text-align: left">
       	Uma lista de identificadores, como publicação, identificador único global (ORCID, DOI etc), URI e outros, de mídias associadas à informação sobre o uso do táxon.
      </td>
    </tr>
    <tr>
      <td style="text-align: left">Domínio</td>
      <td style="text-align: left"></td>
    </tr>
    <tr>
      <td style="text-align: left">Exemplos</td>
      <td style="text-align: left">
        <ul>
          <li>
            Ponto centróide (Estado, Município ou Localidade) para obtenção de
            coordenada
          </li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

---
#### literaturereferences or associatedReferences
<table>
  <tr ="table-secondary">
    <th colspan="2">
      <a href="https://github.com/sibbr/DarwinCoreBrasil/issues/19"
        >associatedReferences</a
      >
    </th>
  </tr>
  <tr>
    <td style="text-align: left">Identificador</td>
    <td style="text-align: left">
      <a href="https://dwc.tdwg.org/terms/#dwc:dynamicProperties"
        >https://dwc.tdwg.org/terms/#dwc:dynamicProperties</a
      >
    </td>
  </tr>
  <tbody>
    <tr>
      <td style="text-align: left">Definição</td>
      <td style="text-align: left">
        Uma lista (concatenada e separada) de identificadores (publicação, referência bibliográfica, identificador único global, URI) da literatura associada à dwc:Occurrence.
      </td>
    </tr>
    <tr>
      <td style="text-align: left">Domínio</td>
      <td style="text-align: left">
        <a href="https://www.json.org/json-pt.html">Formato JSON</a>
      </td>
    </tr>
    <tr>
      <td style="text-align: left">Exemplos</td>
      <td style="text-align: left">
        <ul>
          <li>
            <a
              href="https://ala-hub.sibbr.gov.br/ala-hub/occurrences/a9de20cb-0803-4f7c-bcf8-6cab6a27a959"
              >{"barcode":"ALCB020180"}</a
            >
            <li>
            {"DAP (cm)":30, "Altura (m)":2.5}
            </li>
            <li>
            {"Cor da flor":"amarela"}
            </li>
          </li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

---
