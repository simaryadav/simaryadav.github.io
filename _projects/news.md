---
title: News
date: 2024-01-05 08:01:35 +0300
label: 
image: '/images/newspage.png'
featured:
---

<style>
  /* Define styles for summary and list */
.summary {
    font-size: 28px;
    font-weight: 600;
    padding: 10px 0;
    position: sticky;
    top: 0;
    text-align: center;
    height: calc(10vw + 20px);
    transition: all 0.2s ease-in;
}

.details {
    margin-bottom: 20px;
    border-bottom: 1px solid #ccc;
    padding-bottom: 10px;
* {
	box-sizing: border-box;
}
ul.gradient-list {
  counter-reset: gradient-counter;
  list-style: none;
  margin: 1.75rem 0;
  padding-left: 1rem;
  > li {
    background: white;
    border-radius: 0 0.5rem 0.5rem 0.5rem;
    @extend %boxshadow;
    counter-increment: gradient-counter;
    margin-top: 1rem;
    min-height: 3rem;
    padding: 1rem 1rem 1rem 3rem;
    position: relative;
    &::before,
    &::after {
      background: linear-gradient(135deg, $blue 0%,$green 100%);
      border-radius: 1rem 1rem 0 1rem;
      content: '';
      height: 3rem;
      left: -1rem;
      overflow: hidden;
      position: absolute;
      top: -1rem;
      width: 3rem;
    }
    &::before {
      align-items: flex-end;
      @extend %boxshadow;
      content: counter(gradient-counter);
      color: $black;
      display: flex;
      font: 900 1.5em/1 'Montserrat';
      justify-content: flex-end;
      padding: 0.125em 0.25em;
      z-index: 1;
    }
    @for $i from 1 through 5 {
      &:nth-child(10n+#{$i}):before {
        background: linear-gradient(135deg, rgba($green, $i * 0.2) 0%,rgba($yellow, $i * 0.2) 100%);
      }
    }
    @for $i from 6 through 10 {
      &:nth-child(10n+#{$i}):before {
        background: linear-gradient(135deg, rgba($green, 1 - (($i - 5) * 0.2)) 0%,rgba($yellow, 1 - (($i - 5) * 0.2)) 100%);
      }
    }
    + li {
      margin-top: 2rem;
    }
  }
}
}
}


</style>


<div class = "wrapper">
<div class = "list">
<details>
  <summary style="font-size: 35px; margin-bottom: 15px;">Happenings by Year</summary>
  
<details>
  <summary style="font-size: 28px; margin-bottom: 10px;">2024</summary>
  
  <ul class = "gradient-list" style="font-size: 20px; margin-left: 20px;">
    <li style="font-size: 20px;">February 2024-We published “SLIDE: Significant Latent factor Interaction Discovery and Exploration across biological domains” in Nature Methods.</li>
  </ul>
</details>

<details>
  <summary style="font-size: 28px; margin-bottom: 10px;">2023</summary>
  
  <ul class = "gradient-list" style="font-size: 20px; margin-left: 20px;">
    <li style="font-size: 20px;">December 2023-We published “From bench to bedside via bytes: multi-omic immunoprofiling and integration using machine learning and network approaches” in Human Vaccines and Immunotherapeutics.</li>
    <li style="font-size: 20px;">December 2023-We contributed to “PRMT blockade induces defective DNA replication stress response and synergizes with PARP inhibition”, which was published in Cell Reports Medicine.</li>
    <li style="font-size: 20px;">November 2023-We contributed to “SARS-CoV2 mRNA vaccines induce greater complement activation and decreased viremia and Nef antibodies in men with HIV-1”,which was published in The Journal of Infectious Diseases.</li>
    <li style="font-size: 20px;">October 2023-Jishnu gave an invited talk at BMES 2023 on, "Elucidating humoral profiles associated with Schistosomiasis pathogenesis using interpretable machine learning".</li>
    <li style="font-size: 20px;">October 2023-Jishnu gave an invited talk at BMES 2023 on, "Significant latent factor interaction discovery and exploration across biological domains".</li>
    <li style="font-size: 20px;">August 2023-We published “Cell Type-Specific Biomarkers of Systemic Sclerosis Disease Severity Capture Cell-Intrinsic and Cell-Extrinsic Circuits” in Arthritis & Rheumatology.</li>
    <li style="font-size: 20px;">August 2023-We contributed to “Stability and heterogeneity in the antimicrobiota reactivity of human milk-derived immunoglobulin A”, which got published in the Journal of Experimental Medicine.</li>
    <li style="font-size: 20px;">July 2023-We contributed to “The gut protist Tritrichomonas arnold restrains virus-mediated loss of oral tolerance by modulating dietary antigen-presenting dendritic cells”, which got published in Immunity.</li>
    <li style="font-size: 20px;">June 2023-We published“Antibodies targeting conserved non-canonical antigens and endemic coronaviruses associate with favorable outcomes in severe COVID-19" in Cell Reports.</li>
    <li style="font-size: 20px;">May 2023-Jishnu gave an invited talk at FASEB Autoimmunity 2023 on , "Multi-dimensional integration of protein interactomes with genomic and molecular data discover distinct RA endotypes".</li>
    <li style="font-size: 20px;">March 2023-Jishnu gave an invited talk at Cold Spring Harbor Laboratory Network Biology Meeting 2023 on "Uncovering immunomodulatory molecular phenotypes in infectious disease using networks".</li>
    <li style="font-size: 20px;">April 2023-Jishnu gave an invited talk at Cold Spring Harbor Laboratory Systems Immunology Meeting 2023 on "Multi-dimensional integration of protein interactomes with genomic and molecular data discovers distinct RA endotypes".</li>
    <li style="font-size: 20px;">April 2023-We contributed to “Antibodies against the Ebola virus soluble glycoprotein are associated with long-term vaccine-mediated protection of non-human primates”, which got published in the Cell Reports.</li>
    <li style="font-size: 20px;">February 2023-We contributed to “High-dimensional proteomics identifies organ injury patterns associated with outcomes in human trauma”, which got published in the The Journal of Trauma and Acute Care Surgery.</li>
  </ul>
</details>

<details>
  <summary style="font-size: 28px; margin-bottom: 10px;">2022</summary>
  
  <ul class = "gradient-list" style="font-size: 20px; margin-left: 20px;">
    <li style="font-size: 20px;">October 2022-Jishnu is a Co-I at Systemic Sclerosis Center for Research and Translation which provides machine learning and network systems expertise to investigators working on SSc, SSc-ILD and SSc-PAH.</li>
    <li style="font-size: 20px;">October 2022-Jishnu is a Co-I on the U01 Grant funded to characterize cell-intrinsic and cell-extrinsic signaling circuits in ocular disorders.</li>
    <li style="font-size: 20px;">September 2022-Jishnu gave an invited talk at the Banff-CST Joint Transplant and Pathology Summit titled “Machine learning in clinical decision making in transplant biology”.</li>
    <li style="font-size: 20px;">August 2022-We published A supervised take on dimensionality reduction via hybrid subset selection in Patterns.</li>
    <li style="font-size: 20px;">August 2022-Jishnu gave a talk at International Workshop on Scleroderma 2022 in Boston.</li>
    <li style="font-size: 20px;">July 2022-Jishnu was invited to give a talk at ISMB 2022 on the topic “A network-based approach to identify expression modules underlying rejection in pediatric liver transplantation”.</li>
    <li style="font-size: 20px;">July 2022-Scleroderma CDMRO Award was given to Jishnu (role: Co-I).</li>
    <li style="font-size: 20px;">July 2022-The Philadelphia Enquirer covered our very recent publication on COVID-19.</li>
    <li style="font-size: 20px;">July 2022-Our work got covered in Pittsburgh's Action 4 News "4 Your Health: Studying COVID-19 antibody patterns".</li>
    <li style="font-size: 20px;">July 2022-Jishnu becomes a co-Director for the Systems Immunology Core (funded by NIAMS P50) which will perform machine learning and network systems analyses on multi-modal datasets in the context of SSc.</li>
    <li style="font-size: 20px;">June 2022-Our paper Multi-Omic Admission-Based Prognostic Biomarkers Identified by Machine Learning Algorithms Predict Patient Recovery and 30>Day Survival in Trauma Patients got accepted in Metabolites</li>
    <li style="font-size: 20px;">June 2022-Our paper High Dimensional Multi-omics Reveals Unique Characteristics of Early Plasma Administration in Polytrauma Patients with TBI got accepted in Annals of Surgery</li>
    <li style="font-size: 20px;">June 2022-We published Antibodies targeting conserved non-canonical antigens and endemic coronaviruses associated with favorable outcomes in severe COVID-19 in Cell Press.</li>
    <li style="font-size: 20px;">May 2022-We found out that our NIAID Flu Systems Vaccinology R01 (Role: MPI, other PIs: Alcorn, Singh, Zimmerman) will be funded.</li>
    <li style="font-size: 20px;">May 2022-We participated in a Pitt-Case Western CFAR application that was funded by NIAID Rustbelt (Role: c-I).</li>
    <li style="font-size: 20px;">May 2022-We contributed to Autoreactive CD8+ T cells are restrained by an exhaustion-like program that is maintained by LAG3  which got published in the Nature Immunology.</li>
    <li style="font-size: 20px;">April 2022-Our CIHR grant (Role: co-I, PI: Konvalinka) was funded).</li>
    <li style="font-size: 20px;">April 2022-We published a manuscript in Cell Reports Medicine demonstrating how integrating bulk RNA-seq data with protein networks can uncover signatures underlying rejection in pediatric liver transplantation.</li>
    <li style="font-size: 20px;">March 2022-Our DoD grant (Role: co-I, PIs: Lafyatis and Singh) looking at multi-omic signatures of scleroderma disease severity was funded.</li>
    <li style="font-size: 20px;">March 2022- Our Essential Regression manuscript was published in Patterns.</li>
  </ul>
</details>

<details>
  <summary style="font-size: 28px; margin-bottom: 10px;">2021</summary>
  
  <ul class = "gradient-list" style="font-size: 20px; margin-left: 20px;">
    <li style="font-size: 20px;">September 2021-A NIAID R01 we participated in (Role: co-I, PIs: Rinaldo and Mailliard) looking at COVID-19 vaccine responses in HIV individuals was funded.</li>
    <li style="font-size: 20px;">September 2021-We received a 5-year NHGRI U01 1U01HG012041-01 (Role: MPI, Other PIs: Singh, Sahni)- Link on NIH Reporter.</li>
    <li style="font-size: 20px;">August 2021-We received a 5-year NIAID New Innovator DP2 Award 1DP2AI164325-01 (Role: PI)- Link on NIH Reporter.</li>
    <li style="font-size: 20px;">June 2021-An NIDDK dkNET New Investigator Pilot Program in Bioinformatics grant that we participated in has been funded (Role: co-I, PI: Joglekar).</li>
    <li style="font-size: 20px;">June 2021-We contributed to Mechanisms of impaired lung development and ciliation in Mannosidase-1-alpha-2 (Man1a2) mutants in Frontiers in Physiology.</li>
    <li style="font-size: 20px;">April 2021-Jishnu gave a talk at the 2021 Cold Spring Harbor Systems Immunology Meeting.</li>
    <li style="font-size: 20px;">April 2021-A Department of Defense Idea Development Award grant that we participated in has been funded (Role: co-I, PI: Lafyatis).</li>
    <li style="font-size: 20px;">March 2021-Jishnu gave a talk at the 2021 Cold Spring Harbor Networks Meeting.</li>
  </ul>
</details>

<details>
  <summary style="font-size: 28px; margin-bottom: 10px;">2020</summary>
  
  <ul class = "gradient-list" style="font-size: 20px; margin-left: 20px;">
    <li style="font-size: 20px;">October 2020-We published Mining for humoral correlates of HIV control and latent reservoir size in PLoS pathogens.</li>
    <li style="font-size: 20px;">September 2020-We contributed to Extracellular Matrix Injury of Kidney Allografts in Antibody-Mediated Rejection: A Proteomics Study, which was published in the Journal of the American Society of Nephrology.</li>
    <li style="font-size: 20px;">August 2020-We are now supported by a Collaborative Research Agreement with the University of Brussels Center for Research In Immunology (Role: PI)!</li>
    <li style="font-size: 20px;">July 2020-We contributed to Glucosylation by the Legionella effector SetA promotes the nuclear localization of the transcription factor TFEB, which was published in Science.</li>
    <li style="font-size: 20px;">July 2020-We published Mapping functional humoral correlates of protection against malaria challenge following RTS, S/AS01 vaccination in Science Translational Medicine.</li>
    <li style="font-size: 20px;">June 2020-We received a pilot Covid-19 grant from the UPMC-ITTC (Role: PI)!</li>
    <li style="font-size: 20px;">May 2020-We contributed to Co-immunization of DNA and Protein in the Same Anatomical Sites Induces Superior Protective Immune Responses against SHIV Challenge, which was published in Cell Reports.</li>
    <li style="font-size: 20px;">March 2020-We contributed to Latency reversal agents modulate HIV antigen processing and presentation to CD8 T cells, which was published in PLoS pathogens.</li>
    <li style="font-size: 20px;">March 2020-We contributed to Epigenetic basis for monocyte dysfunction in patients with severe alcoholic hepatitis, which was published in the Journal of Hepatology.</li>
    <li style="font-size: 20px;">February 2020-We published Antibody Fc Glycosylation Discriminates Between Latent and Active Tuberculosis in The Journal of Infectious Diseases.</li>
    <li style="font-size: 20px;">January 2020-The Das Systems Immunology Lab is now supported by Center for Systems Immunology Startup Funds!</li>
    <li style="font-size: 20px;">January 2020-The lab is now open! We look forward to exciting science in the future!</li>
  </ul>
</details>
</details>


<details>
  <summary style="font-size: 35px; margin-bottom: 15px;">Happenings by events</summary>
<details>
  <summary style="font-size: 28px; margin-bottom: 10px;">Publications</summary>
  <ul class = "gradient-list" style="font-size: 20px; margin-left: 20px;">
    <li style="font-size: 20px;">December 2023-We published “From bench to bedside via bytes: multi-omic immunoprofiling and integration using machine learning and network approaches” in Human Vaccines and Immunotherapeutics.</li>
    <li style="font-size: 20px;">December 2023-We contributed to “PRMT blockade induces defective DNA replication stress response and synergizes with PARP inhibition”, which was published in Cell Reports Medicine.</li>
    <li style="font-size: 20px;">November 2023-We contributed to “SARS-CoV2 mRNA vaccines induce greater complement activation and decreased viremia and Nef antibodies in men with HIV-1”,which was published in The Journal of Infectious Diseases.</li>
    <li style="font-size: 20px;">October 2023-We published “Cell Type-Specific Biomarkers of Systemic Sclerosis Disease Severity Capture Cell-Intrinsic and Cell-Extrinsic Circuits” in Arthritis & Rheumatology.</li>
    <li style="font-size: 20px;">October 2023-We contributed to “Stability and heterogeneity in the antimicrobiota reactivity of human milk-derived immunoglobulin A”, which got published in the Journal of Experimental Medicine.</li>
    <li style="font-size: 20px;">July 2023-We contributed to “The gut protist Tritrichomonas arnold restrains virus-mediated loss of oral tolerance by modulating dietary antigen-presenting dendritic cells”, which got published in Immunity.</li>
    <li style="font-size: 20px;">June 2023-We published“Antibodies targeting conserved non-canonical antigens and endemic coronaviruses associate with favorable outcomes in severe COVID-19" in Cell Reports.</li>
    <li style="font-size: 20px;">February 2023-We contributed to “High-dimensional proteomics identifies organ injury patterns associated with outcomes in human trauma”, which got published in the The Journal of Trauma and Acute Care Surgery.</li>
    <li style="font-size: 20px;">April 2023-We contributed to “Antibodies against the Ebola virus soluble glycoprotein are associated with long-term vaccine-mediated protection of non-human primates”, which got published in the Cell Reports.</li>
    <li style="font-size: 20px;">April 2023-We published a manuscript in Cell Reports Medicine demonstrating how integrating bulk RNA-seq data with protein networks can uncover signatures underlying rejection in pediatric liver transplantation.</li>
    <li style="font-size: 20px;">May 2022-We found out that our NIAID Flu Systems Vaccinology R01 (Role: MPI, other PIs: Alcorn, Singh, Zimmerman) will be funded.</li>
    <li style="font-size: 20px;">May 2022-We participated in a Pitt-Case Western CFAR application that was funded by NIAID Rustbelt (Role: c-I).</li>
    <li style="font-size: 20px;">May 2022-We contributed to Autoreactive CD8+ T cells are restrained by an exhaustion-like program that is maintained by LAG3  which got published in the Nature Immunology.</li>
    <li style="font-size: 20px;">April 2022-Our CIHR grant (Role: co-I, PI: Konvalinka) was funded).</li>
    <li style="font-size: 20px;">April 2022-We published a manuscript in Cell Reports Medicine demonstrating how integrating bulk RNA-seq data with protein networks can uncover signatures underlying rejection in pediatric liver transplantation.</li>
    <li style="font-size: 20px;">March 2022-Our DoD grant (Role: co-I, PIs: Lafyatis and Singh) looking at multi-omic signatures of scleroderma disease severity was funded.</li>
    <li style="font-size: 20px;">March 2022- Our Essential Regression manuscript was published in Patterns.</li>
    <li style="font-size: 20px;">October 2020-We published Mining for humoral correlates of HIV control and latent reservoir size in PLoS pathogens.</li>
    <li style="font-size: 20px;">September 2020-We contributed to Extracellular Matrix Injury of Kidney Allografts in Antibody-Mediated Rejection: A Proteomics Study, which was published in the Journal of the American Society of Nephrology.</li>
    <li style="font-size: 20px;">July 2020-We contributed to Glucosylation by the Legionella effector SetA promotes the nuclear localization of the transcription factor TFEB, which was published in Science.</li>
    <li style="font-size: 20px;">July 2020-We published Mapping functional humoral correlates of protection against malaria challenge following RTS, S/AS01 vaccination in Science Translational Medicine.</li>
    <li style="font-size: 20px;">May 2020-We contributed to Co-immunization of DNA and Protein in the Same Anatomical Sites Induces Superior Protective Immune Responses against SHIV Challenge, which was published in Cell Reports.</li>
    <li style="font-size: 20px;">March 2020-We contributed to Latency reversal agents modulate HIV antigen processing and presentation to CD8 T cells, which was published in PLoS pathogens.</li>
    <li style="font-size: 20px;">March 2020-We contributed to Epigenetic basis for monocyte dysfunction in patients with severe alcoholic hepatitis, which was published in the Journal of Hepatology.</li>
    <li style="font-size: 20px;">February 2020-We published Antibody Fc Glycosylation Discriminates Between Latent and Active Tuberculosis in The Journal of Infectious Diseases.</li>
  </ul>
</details>

<details>
  <summary style="font-size: 28px; margin-bottom: 10px;">Grants</summary>
  <ul class = "gradient-list" style="font-size: 20px; margin-left: 20px;">
    <li style="font-size: 20px;">October 2022-Jishnu is a Co-I at Systemic Sclerosis Center for Research and Translation which provides machine learning and network systems expertise to investigators working on SSc, SSc-ILD and SSc-PAH.</li>
    <li style="font-size: 20px;">October 2022-Jishnu is a Co-I on the U01 Grant funded to characterize cell-intrinsic and cell-extrinsic signaling circuits in ocular disorders.</li>
    <li style="font-size: 20px;">September 2022-Jishnu gave an invited talk at the Banff-CST Joint Transplant and Pathology Summit titled “Machine learning in clinical decision making in transplant biology”.</li>
    <li style="font-size: 20px;">August 2022-Jishnu gave a talk at International Workshop on Scleroderma 2022 in Boston.</li>
    <li style="font-size: 20px;">July 2022-Jishnu was invited to give a talk at ISMB 2022 on the topic “A network-based approach to identify expression modules underlying rejection in pediatric liver transplantation”.</li>
    <li style="font-size: 20px;">July 2022-Scleroderma CDMRO Award was given to Jishnu (role: Co-I).</li>
    <li style="font-size: 20px;">July 2022-The Philadelphia Enquirer covered our very recent publication on COVID-19.</li>
    <li style="font-size: 20px;">July 2022-Our work got covered in Pittsburgh's Action 4 News "4 Your Health: Studying COVID-19 antibody patterns".</li>
    <li style="font-size: 20px;">July 2022-Jishnu becomes a co-Director for the Systems Immunology Core (funded by NIAMS P50) which will perform machine learning and network systems analyses on multi-modal datasets in the context of SSc.</li>
    <li style="font-size: 20px;">June 2022-Our paper Multi-Omic Admission-Based Prognostic Biomarkers Identified by Machine Learning Algorithms Predict Patient Recovery and 30>Day Survival in Trauma Patients got accepted in Metabolites</li>
    <li style="font-size: 20px;">June 2022-Our paper High Dimensional Multi-omics Reveals Unique Characteristics of Early Plasma Administration in Polytrauma Patients with TBI got accepted in Annals of Surgery</li>
    <li style="font-size: 20px;">June 2022-We published Antibodies targeting conserved non-canonical antigens and endemic coronaviruses associated with favorable outcomes in severe COVID-19 in Cell Press.</li>
    <li style="font-size: 20px;">May 2022-We found out that our NIAID Flu Systems Vaccinology R01 (Role: MPI, other PIs: Alcorn, Singh, Zimmerman) will be funded.</li>
    <li style="font-size: 20px;">May 2022-We participated in a Pitt-Case Western CFAR application that was funded by NIAID Rustbelt (Role: c-I).</li>
    <li style="font-size: 20px;">May 2022-We contributed to Autoreactive CD8+ T cells are restrained by an exhaustion-like program that is maintained by LAG3  which got published in the Nature Immunology.</li>
    <li style="font-size: 20px;">April 2022-Our CIHR grant (Role: co-I, PI: Konvalinka) was funded).</li>
    <li style="font-size: 20px;">April 2022-We published a manuscript in Cell Reports Medicine demonstrating how integrating bulk RNA-seq data with protein networks can uncover signatures underlying rejection in pediatric liver transplantation.</li>
    <li style="font-size: 20px;">March 2022-Our DoD grant (Role: co-I, PIs: Lafyatis and Singh) looking at multi-omic signatures of scleroderma disease severity was funded.</li>
    <li style="font-size: 20px;">March 2022- Our Essential Regression manuscript was published in Patterns.</li>
  </ul>
</details>

<details>
  <summary style="font-size: 28px; margin-bottom: 10px;">Talks</summary>
  <ul class = "gradient-list" style="font-size: 20px; margin-left: 20px;">
    <li style="font-size: 20px;">October 2023-Jishnu gave an invited talk at BMES 2023 on, "Elucidating humoral profiles associated with Schistosomiasis pathogenesis using interpretable machine learning".</li>
    <li style="font-size: 20px;">October 2023-Jishnu gave an invited talk at BMES 2023 on, "Significant latent factor interaction discovery and exploration across biological domains".</li>
    <li style="font-size: 20px;">August 2022-Jishnu gave a talk at International Workshop on Scleroderma 2022 in Boston.</li>
    <li style="font-size: 20px;">July 2022-Jishnu was invited to give a talk at ISMB 2022 on the topic “A network-based approach to identify expression modules underlying rejection in pediatric liver transplantation”.</li>
    <li style="font-size: 20px;">June 2021-An NIDDK dkNET New Investigator Pilot Program in Bioinformatics grant that we participated in has been funded (Role: co-I, PI: Joglekar).</li>
    <li style="font-size: 20px;">June 2021-We contributed to Mechanisms of impaired lung development and ciliation in Mannosidase-1-alpha-2 (Man1a2) mutants in Frontiers in Physiology.</li>
    <li style="font-size: 20px;">April 2021-Jishnu gave a talk at the 2021 Cold Spring Harbor Systems Immunology Meeting.</li>
    <li style="font-size: 20px;">April 2021-A Department of Defense Idea Development Award grant that we participated in has been funded (Role: co-I, PI: Lafyatis).</li>
    <li style="font-size: 20px;">March 2021-Jishnu gave a talk at the 2021 Cold Spring Harbor Networks Meeting.</li>
    <li style="font-size: 20px;">January 2020-The Das Systems Immunology Lab is now supported by Center for Systems Immunology Startup Funds!</li>
    <li style="font-size: 20px;">January 2020-The lab is now open! We look forward to exciting science in the future!</li>
  </ul>
</details>
</details>
</div>
</div>