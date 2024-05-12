---
title: News
date: 2024-01-05 08:01:35 +0300
label:
image: '/images/newspage.png'
featured:
---
<style>
  /* Styling for the text box */

  /* Styling for the buttons */
  .button-container {
    margin-bottom: 20px;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .but {
    padding: 6px 16px;
    margin: 4px 8px 4px 0;
    font-size: 12px;
    font-weight: 500;
    text-transform: capitalize;
    border-radius: 60px;
    color: var(--heading-font-color);
    transition: all 0.2s;
    background-color: var(--background-alt-color);
  }

  .button:hover {
    background-color: #0056b3;
    display: inline-flex;
    align-items: center;
    flex-wrap: wrap;
  }

  .textbox {
    overflow: auto;
    width: 100%;
    height: 300px;
    font-size: medium;
    padding: 0.8rem 1rem;
    border-radius: 30px;
  }

</style>

<body>

<!-- Button container -->
<div class="button-container">
  <!-- Button for Papers -->
  <button class = "tag-button" onclick="showPapers()">Papers</button>
  <!-- Button for Grants -->
  <button class = "tag-button" onclick="showGrants()">Grants</button>
  <!-- Button for Talks -->
  <button class = "tag-button" onclick="showTalks()">Talks</button><br>
</div>

<!-- Button container -->
<div class="button-container">
  
  <button class = "tag-button" onclick="show2024()">2024</button>
  <!-- Button for 2023 -->
  <button class = "tag-button" onclick="show2023()">2023</button>
  <!-- Button for 2022 -->
  <button class = "tag-button" onclick="show2022()">2022</button>
  <!-- Button for 2021 -->
  <button class = "tag-button" onclick="show2021()">2021</button>
  <!-- Button for 2020 -->
  <button class = "tag-button" onclick="show2020()">2020</button>

</div>
<!-- JavaScript functions to display category information -->
<script>
// Function to show Papers information
function showPapers() {
    var textBox = document.getElementById("output");
    var papersData = `December 2023-We published “From bench to bedside via bytes: multi-omic immunoprofiling and integration using machine learning and network approaches” in Human Vaccines and Immunotherapeutics.

December 2023-We contributed to “PRMT blockade induces defective DNA replication stress response and synergizes with PARP inhibition”, which was published in Cell Reports Medicine.

November 2023-We contributed to “SARS-CoV2 mRNA vaccines induce greater complement activation and decreased viremia and Nef antibodies in men with HIV-1”,which was published in The Journal of Infectious Diseases.

October 2023-We published “Cell Type-Specific Biomarkers of Systemic Sclerosis Disease Severity Capture Cell-Intrinsic and Cell-Extrinsic Circuits” in Arthritis & Rheumatology.

October 2023-We contributed to “Stability and heterogeneity in the antimicrobiota reactivity of human milk-derived immunoglobulin A”, which got published in the Journal of Experimental Medicine.

July 2023-We contributed to “The gut protist Tritrichomonas arnold restrains virus-mediated loss of oral tolerance by modulating dietary antigen-presenting dendritic cells”, which got published in Immunity.

June 2023-We published“Antibodies targeting conserved non-canonical antigens and endemic coronaviruses associate with favorable outcomes in severe COVID-19" in Cell Reports.

February 2023-We contributed to “High-dimensional proteomics identifies organ injury patterns associated with outcomes in human trauma”, which got published in the The Journal of Trauma and Acute Care Surgery.

April 2023-We contributed to “Antibodies against the Ebola virus soluble glycoprotein are associated with long-term vaccine-mediated protection of non-human primates”, which got published in the Cell Reports.

April 2023-We published a manuscript in Cell Reports Medicine demonstrating how integrating bulk RNA-seq data with protein networks can uncover signatures underlying rejection in pediatric liver transplantation.

May 2022-We found out that our NIAID Flu Systems Vaccinology R01 (Role: MPI, other PIs: Alcorn, Singh, Zimmerman) will be funded.

May 2022-We participated in a Pitt-Case Western CFAR application that was funded by NIAID Rustbelt (Role: c-I).

May 2022-We contributed to Autoreactive CD8+ T cells are restrained by an exhaustion-like program that is maintained by LAG3  which got published in the Nature Immunology.

April 2022-Our CIHR grant (Role: co-I, PI: Konvalinka) was funded).

April 2022-We published a manuscript in Cell Reports Medicine demonstrating how integrating bulk RNA-seq data with protein networks can uncover signatures underlying rejection in pediatric liver transplantation.

March 2022-Our DoD grant (Role: co-I, PIs: Lafyatis and Singh) looking at multi-omic signatures of scleroderma disease severity was funded.

March 2022- Our Essential Regression manuscript was published in Patterns.

October 2020-We published Mining for humoral correlates of HIV control and latent reservoir size in PLoS pathogens.

September 2020-We contributed to Extracellular Matrix Injury of Kidney Allografts in Antibody-Mediated Rejection: A Proteomics Study, which was published in the Journal of the American Society of Nephrology.

July 2020-We contributed to Glucosylation by the Legionella effector SetA promotes the nuclear localization of the transcription factor TFEB, which was published in Science.

July 2020-We published Mapping functional humoral correlates of protection against malaria challenge following RTS, S/AS01 vaccination in Science Translational Medicine.

May 2020-We contributed to Co-immunization of DNA and Protein in the Same Anatomical Sites Induces Superior Protective Immune Responses against SHIV Challenge, which was published in Cell Reports.

March 2020-We contributed to Latency reversal agents modulate HIV antigen processing and presentation to CD8 T cells, which was published in PLoS pathogens.

March 2020-We contributed to Epigenetic basis for monocyte dysfunction in patients with severe alcoholic hepatitis, which was published in the Journal of Hepatology.

February 2020-We published Antibody Fc Glycosylation Discriminates Between Latent and Active Tuberculosis in The Journal of Infectious Diseases.`;
    textBox.value = papersData;
}
//Function to show Grants information
function showGrants() {
    var textBox = document.getElementById("output");
    var grantsData = `October 2022-Jishnu is a Co-I at Systemic Sclerosis Center for Research and Translation which provides machine learning and network systems expertise to investigators working on SSc, SSc-ILD and SSc-PAH.

October 2022-Jishnu is a Co-I on the U01 Grant funded to characterize cell-intrinsic and cell-extrinsic signaling circuits in ocular disorders.

September 2022-Jishnu gave an invited talk at the Banff-CST Joint Transplant and Pathology Summit titled “Machine learning in clinical decision making in transplant biology”.

August 2022-Jishnu gave a talk at International Workshop on Scleroderma 2022 in Boston.

July 2022-Jishnu was invited to give a talk at ISMB 2022 on the topic “A network-based approach to identify expression modules underlying rejection in pediatric liver transplantation”.

July 2022-Scleroderma CDMRO Award was given to Jishnu (role: Co-I).

July 2022-The Philadelphia Enquirer covered our very recent publication on COVID-19.

July 2022-Our work got covered in Pittsburgh's Action 4 News "4 Your Health: Studying COVID-19 antibody patterns".

July 2022-Jishnu becomes a co-Director for the Systems Immunology Core (funded by NIAMS P50) which will perform machine learning and network systems analyses on multi-modal datasets in the context of SSc.

June 2022-Our paper Multi-Omic Admission-Based Prognostic Biomarkers Identified by Machine Learning Algorithms Predict Patient Recovery and 30>Day Survival in Trauma Patients got accepted in Metabolites

June 2022-Our paper High Dimensional Multi-omics Reveals Unique Characteristics of Early Plasma Administration in Polytrauma Patients with TBI got accepted in Annals of Surgery

June 2022-We published Antibodies targeting conserved non-canonical antigens and endemic coronaviruses associated with favorable outcomes in severe COVID-19 in Cell Press.

May 2022-We found out that our NIAID Flu Systems Vaccinology R01 (Role: MPI, other PIs: Alcorn, Singh, Zimmerman) will be funded.

May 2022-We participated in a Pitt-Case Western CFAR application that was funded by NIAID Rustbelt (Role: c-I).

May 2022-We contributed to Autoreactive CD8+ T cells are restrained by an exhaustion-like program that is maintained by LAG3  which got published in the Nature Immunology.

April 2022-Our CIHR grant (Role: co-I, PI: Konvalinka) was funded).

April 2022-We published a manuscript in Cell Reports Medicine demonstrating how integrating bulk RNA-seq data with protein networks can uncover signatures underlying rejection in pediatric liver transplantation.

March 2022-Our DoD grant (Role: co-I, PIs: Lafyatis and Singh) looking at multi-omic signatures of scleroderma disease severity was funded.

March 2022- Our Essential Regression manuscript was published in Patterns.`;
    textBox.value = grantsData;
}
// Function to show Talks information
function showTalks() {
    var textBox = document.getElementById("output");
    var talksData = `October 2023-Jishnu gave an invited talk at BMES 2023 on, "Elucidating humoral profiles associated with Schistosomiasis pathogenesis using interpretable machine learning".

October 2023-Jishnu gave an invited talk at BMES 2023 on, "Significant latent factor interaction discovery and exploration across biological domains".

August 2022-Jishnu gave a talk at International Workshop on Scleroderma 2022 in Boston.

July 2022-Jishnu was invited to give a talk at ISMB 2022 on the topic “A network-based approach to identify expression modules underlying rejection in pediatric liver transplantation”.

June 2021-An NIDDK dkNET New Investigator Pilot Program in Bioinformatics grant that we participated in has been funded (Role: co-I, PI: Joglekar).

June 2021-We contributed to Mechanisms of impaired lung development and ciliation in Mannosidase-1-alpha-2 (Man1a2) mutants in Frontiers in Physiology.

April 2021-Jishnu gave a talk at the 2021 Cold Spring Harbor Systems Immunology Meeting.

April 2021-A Department of Defense Idea Development Award grant that we participated in has been funded (Role: co-I, PI: Lafyatis).

March 2021-Jishnu gave a talk at the 2021 Cold Spring Harbor Networks Meeting.

January 2020-The Das Systems Immunology Lab is now supported by Center for Systems Immunology Startup Funds!

January 2020-The lab is now open! We look forward to exciting science in the future!`;
    textBox.value = talksData;
}
// Function to show 2024 information
function show2024() {
    var textBox = document.getElementById("output");
    var data2024 = `February 2024-We published “SLIDE: Significant Latent factor Interaction Discovery and Exploration across biological domains” in Nature Methods.`;
    textBox.value = data2024;
}
// Function to show 2023 information
function show2023() {
    var textBox = document.getElementById("output");
    var data2023 = `December 2023-We published “From bench to bedside via bytes: multi-omic immunoprofiling and integration using machine learning and network approaches” in Human Vaccines and Immunotherapeutics.

December 2023-We contributed to “PRMT blockade induces defective DNA replication stress response and synergizes with PARP inhibition”, which was published in Cell Reports Medicine.

November 2023-We contributed to “SARS-CoV2 mRNA vaccines induce greater complement activation and decreased viremia and Nef antibodies in men with HIV-1”,which was published in The Journal of Infectious Diseases.

October 2023-Jishnu gave an invited talk at BMES 2023 on, "Elucidating humoral profiles associated with Schistosomiasis pathogenesis using interpretable machine learning".

October 2023-Jishnu gave an invited talk at BMES 2023 on, "Significant latent factor interaction discovery and exploration across biological domains".

August 2023-We published “Cell Type-Specific Biomarkers of Systemic Sclerosis Disease Severity Capture Cell-Intrinsic and Cell-Extrinsic Circuits” in Arthritis & Rheumatology.

August 2023-We contributed to “Stability and heterogeneity in the antimicrobiota reactivity of human milk-derived immunoglobulin A”, which got published in the Journal of Experimental Medicine.

July 2023-We contributed to “The gut protist Tritrichomonas arnold restrains virus-mediated loss of oral tolerance by modulating dietary antigen-presenting dendritic cells”, which got published in Immunity.

June 2023-We published“Antibodies targeting conserved non-canonical antigens and endemic coronaviruses associate with favorable outcomes in severe COVID-19" in Cell Reports.

May 2023-Jishnu gave an invited talk at FASEB Autoimmunity 2023 on , "Multi-dimensional integration of protein interactomes with genomic and molecular data discover distinct RA endotypes".

March 2023-Jishnu gave an invited talk at Cold Spring Harbor Laboratory Network Biology Meeting 2023 on "Uncovering immunomodulatory molecular phenotypes in infectious disease using networks".

April 2023-Jishnu gave an invited talk at Cold Spring Harbor Laboratory Systems Immunology Meeting 2023 on "Multi-dimensional integration of protein interactomes with genomic and molecular data discovers distinct RA endotypes".

April 2023-We contributed to “Antibodies against the Ebola virus soluble glycoprotein are associated with long-term vaccine-mediated protection of non-human primates”, which got published in the Cell Reports.

February 2023-We contributed to “High-dimensional proteomics identifies organ injury patterns associated with outcomes in human trauma”, which got published in the The Journal of Trauma and Acute Care Surgery.`;
    textBox.value = data2023;
}
// Function to show 2022 information
function show2022() {
    var textBox = document.getElementById("output");
    var data2022 = `October 2022-Jishnu is a Co-I at Systemic Sclerosis Center for Research and Translation which provides machine learning and network systems expertise to investigators working on SSc, SSc-ILD and SSc-PAH.

October 2022-Jishnu is a Co-I on the U01 Grant funded to characterize cell-intrinsic and cell-extrinsic signaling circuits in ocular disorders.

September 2022-Jishnu gave an invited talk at the Banff-CST Joint Transplant and Pathology Summit titled “Machine learning in clinical decision making in transplant biology”.

August 2022-We published A supervised take on dimensionality reduction via hybrid subset selection in Patterns.

August 2022-Jishnu gave a talk at International Workshop on Scleroderma 2022 in Boston.

July 2022-Jishnu was invited to give a talk at ISMB 2022 on the topic “A network-based approach to identify expression modules underlying rejection in pediatric liver transplantation”.

July 2022-Scleroderma CDMRO Award was given to Jishnu (role: Co-I).

July 2022-The Philadelphia Enquirer covered our very recent publication on COVID-19.

July 2022-Our work got covered in Pittsburgh's Action 4 News "4 Your Health: Studying COVID-19 antibody patterns".

July 2022-Jishnu becomes a co-Director for the Systems Immunology Core (funded by NIAMS P50) which will perform machine learning and network systems analyses on multi-modal datasets in the context of SSc.

June 2022-Our paper Multi-Omic Admission-Based Prognostic Biomarkers Identified by Machine Learning Algorithms Predict Patient Recovery and 30>Day Survival in Trauma Patients got accepted in Metabolites

June 2022-Our paper High Dimensional Multi-omics Reveals Unique Characteristics of Early Plasma Administration in Polytrauma Patients with TBI got accepted in Annals of Surgery

June 2022-We published Antibodies targeting conserved non-canonical antigens and endemic coronaviruses associated with favorable outcomes in severe COVID-19 in Cell Press.

May 2022-We found out that our NIAID Flu Systems Vaccinology R01 (Role: MPI, other PIs: Alcorn, Singh, Zimmerman) will be funded.

May 2022-We participated in a Pitt-Case Western CFAR application that was funded by NIAID Rustbelt (Role: c-I).

May 2022-We contributed to Autoreactive CD8+ T cells are restrained by an exhaustion-like program that is maintained by LAG3  which got published in the Nature Immunology.

April 2022-Our CIHR grant (Role: co-I, PI: Konvalinka) was funded).

April 2022-We published a manuscript in Cell Reports Medicine demonstrating how integrating bulk RNA-seq data with protein networks can uncover signatures underlying rejection in pediatric liver transplantation.

March 2022-Our DoD grant (Role: co-I, PIs: Lafyatis and Singh) looking at multi-omic signatures of scleroderma disease severity was funded.

March 2022- Our Essential Regression manuscript was published in Patterns.`;
    textBox.value = data2022;
}

// Function to show 2021 information
function show2021() {
    var textBox = document.getElementById("output");
    var data2021 = `September 2021-A NIAID R01 we participated in (Role: co-I, PIs: Rinaldo and Mailliard) looking at COVID-19 vaccine responses in HIV individuals was funded.

September 2021-We received a 5-year NHGRI U01 1U01HG012041-01 (Role: MPI, Other PIs: Singh, Sahni)- Link on NIH Reporter.

August 2021-We received a 5-year NIAID New Innovator DP2 Award 1DP2AI164325-01 (Role: PI)- Link on NIH Reporter.

June 2021-An NIDDK dkNET New Investigator Pilot Program in Bioinformatics grant that we participated in has been funded (Role: co-I, PI: Joglekar).

June 2021-We contributed to Mechanisms of impaired lung development and ciliation in Mannosidase-1-alpha-2 (Man1a2) mutants in Frontiers in Physiology.

April 2021-Jishnu gave a talk at the 2021 Cold Spring Harbor Systems Immunology Meeting.

April 2021-A Department of Defense Idea Development Award grant that we participated in has been funded (Role: co-I, PI: Lafyatis).

March 2021-Jishnu gave a talk at the 2021 Cold Spring Harbor Networks Meeting.`;
    textBox.value = data2021;
}

// Function to show 2020 information
function show2020() {
    var textBox = document.getElementById("output");
    var data2020 = `October 2020-We published Mining for humoral correlates of HIV control and latent reservoir size in PLoS pathogens.

September 2020-We contributed to Extracellular Matrix Injury of Kidney Allografts in Antibody-Mediated Rejection: A Proteomics Study, which was published in the Journal of the American Society of Nephrology.

August 2020-We are now supported by a Collaborative Research Agreement with the University of Brussels Center for Research In Immunology (Role: PI)!

July 2020-We contributed to Glucosylation by the Legionella effector SetA promotes the nuclear localization of the transcription factor TFEB, which was published in Science.

July 2020-We published Mapping functional humoral correlates of protection against malaria challenge following RTS, S/AS01 vaccination in Science Translational Medicine.

June 2020-We received a pilot Covid-19 grant from the UPMC-ITTC (Role: PI)!

May 2020-We contributed to Co-immunization of DNA and Protein in the Same Anatomical Sites Induces Superior Protective Immune Responses against SHIV Challenge, which was published in Cell Reports.

March 2020-We contributed to Latency reversal agents modulate HIV antigen processing and presentation to CD8 T cells, which was published in PLoS pathogens.

March 2020-We contributed to Epigenetic basis for monocyte dysfunction in patients with severe alcoholic hepatitis, which was published in the Journal of Hepatology.

February 2020-We published Antibody Fc Glycosylation Discriminates Between Latent and Active Tuberculosis in The Journal of Infectious Diseases.

January 2020-The Das Systems Immunology Lab is now supported by Center for Systems Immunology Startup Funds!

January 2020-The lab is now open! We look forward to exciting science in the future!`;

    textBox.value = data2020;
}


</script>
<div class = "text-box">
<!-- Text box -->
<textarea readonly class = "textbox" id="output" placeholder="Text will appear here"></textarea>

</div>
</body>
