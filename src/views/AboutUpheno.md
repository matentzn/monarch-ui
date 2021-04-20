<div class="container-fluid monarch-view monarch-about-view">

<h2 class="page-title">The Unified Phenotype Ontology (uPheno)</h2>
<div class="top-section col-12">
<p>The Unified Phenotype Ontology (uPheno) is an effort led by the Monarch Initiative to integrate phenotype terminologies across species. uPheno has to major components: an OWL ontology that imports and deeply integrates phenotype ontologies from a variety of species, including Human and several major model organisms (such as Drosophila, Zebrafish, Xenopus, C. elegans, and Mouse), and a library of phenotype ontology term templates that are developed by the <a href="https://github.com/obophenotype/upheno/wiki/Phenotype-Ontologies-Reconciliation-Effort">Phenotype Ontologies Reconciliation Effort</a>. 
</p>

<div class="col-12 col-lg-6">
    <figure class="ecosystems">
          <img src="../assets/img/upheno.png"/>
          <figcaption>
          Fig 1. <strong>uPheno template-driven ontology development and harmonization.</strong> A. uPheno templates are used to define phenotypes according to agreed design patterns. B. Computable definitions specified using uPheno templates are used to automate classification of uPheno and parts of ZP (dashed lines) as described in panel D. C. Computable definitions also drive automated classification of HP and ZP classes under uPheno classes. For example, enlarged heart in ZP (defined using the zebrafish anatomy heart term) and enlarged heart in HPO are both classified under uPheno enlarged heart (defined using Uberon heart). Algorithms can use this classification under uPheno to predict that human orthologs of zebrafish genes annotated to enlarged heart may cause enlarged heart in humans. Variant prioritization more typically matches the profile of phenotypes associated with a disease with those associated with variants in a model organism gene using the ontology classification to support statistical matching (Figure 7). D. Automating classification: Terms defined using templates follow a standard design pattern, allowing reasoning software (ELK) to leverage classifications in external ontologies (Uberon and PATO) to classify phenotypes.
          </figcaption>
    </figure>
</div>

<p>uPheno provides a common framework for the representation of phenotype terms and integrates all domain-specific phenotype ontologies into a single, unified, ontology. The common representation framework ensures a rich and consistent axiomatisation that enables expressive querying and effective classification of phenotypes across species and modalities. For example, a user might be interested in grouping all phenotypes related to abnormalities in a metabolic process that occur in a part of the digestive system. Integrating all domain-specific phenotype ontologies in a single, unified resource will drive the following use cases:
<ol>
<li>Cross-species analysis. uPheno enables the straightforward retrieval of both analogous and similar phenotypes across taxons. This can be used for a variety of applications, from finding relevant literature across species to identifying candidate genes for phenotypes with an unknown genetic basis.</li>
<li>Cross-domain phenotype curation: uPheno enables the curation of species-independent phenotypes as well as species-specific ones, which makes it particularly useful in a scenario where multiple taxons are involved.</li>
</ol>
</p>

</div>
</div>

<style lang="scss">
@import "~@/style/variables";

.container-fluid.monarch-view.monarch-about-view {
  h1, h2, h3, h4, h5, h6 {
    clear:both;
  }
  
  .monarch-hr {
    border-top-color: $monarch-bg-color;
    border-top-width: 2px;
  }
  
  
  .goals-banner {
      padding: 20px;
      height: auto;
      margin-top: 25px;
      color: white;
      background-color: $monarch-bg-color;
      border-radius: 0.5rem;
      text-align: center;
  }
  figure {
    margin: 0 auto;
  }
  .callouts {
    margin: 50px 0 50px;
    
    .title {
        text-align: center;
        width: 100%;
    }
    .card {
        text-align: center;
        background-color: #0B556B;
        margin-right: 15px;
        color: white;
        border-radius: 0.5rem !important;
        .card-btn {
            background-color: $monarch-button-color;
            color: black;
        }
    }
  
  }
  
  figure {
    display:table;
    
    &.comparison {
        img {
            max-width: 500px;
        }
    }
    &.cross-species {
        img {
            max-width: 650px;
        }
    }
    
    &.ecosystems {
    
        img {
            max-width: 650px;
        }

        &.phenopackets img {
         max-width: 750px;
        }
    }
    img {
      padding:15px;
      height: auto;
      width: 100%;
    }
  }

  .right {
    float:right;
  }

  .left {
    float:left;
  }

  .center {
    margin-left:auto;
    margin-right:auto;
    vertical-align:middle;
    text-align:center;
  }

  .bottomright {
    float:right;
    position:relative;
    bottom:0;
    right:0;
  }

  figcaption {
    text-align:justify;
    font-size:12px;
    word-wrap:normal;
    display:table-caption;
    caption-side: bottom;
    padding: 0 10px 5px;
    line-height: 16px;
  }
  
  .figure-title {
    text-align: center;
    font-weight: bold;
  }


  table {
    margin: auto;
    text-align: center;
    td a img {
      max-width: 120px;
      margin: 5px;
    }

    @media(min-width:$grid-float-breakpoint) {
      td a img {
        max-width: 200px;
      }
    }
  }
    .phenotype-coverage {
        
    }
}

</style>
