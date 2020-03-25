# Covid-19-Covariation-Analysis

This Covid-19 project has the main idea of reconstituting viral capsid protein and RNA assembly in vitro and finding potential inhibitors. We are looking for people interested to perform a bioinformatic analysis to identify putative RNA packaging signals in Covid-19 using covariation analysis and would have time to work on this basically immediately. At this point we have inferred two stem loops at homologous sites to other coronaviruses, but we would be interested to see if those can be verified and potentially other packaging signal candidates can be identified.

This is the analysis we are interested in. 

<table>
  <tr>
    <th>Task Number</th>
    <th>Task Description</th>
  </tr>
  <tr>
    <td>1</td>
    <td>Download all https://www.gisaid.org coronavirus sequences and individually blast to reference genome.</td>
  </tr>
  <tr>
    <td>2</td>
    <td>Discard any sequences with a sequence divergence (absolute mismatch > 5%)</td>
  </tr>
  <tr>
    <td>3</td>
    <td>If no sequences are discarded at 5% mismatch, lower to 1%.</td>
  </tr>
  <tr>
    <td>4</td>
    <td>Discard any sequences shorter than 80% of reference genome.</td>
  </tr>
  <tr>
    <td>5</td>
    <td>Run CMsearch from infernal package (http://eddylab.org/infernal/) using  https://rfam.org/family/RF00182</td>
  </tr>
  <tr>
    <td>6</td>
    <td>Identify location and “bit-score” of top hit location.</td>
  </tr>
  <tr>
    <td>7</td>
    <td>Plot a bit-score weighted average position on reference genome.</td>
  </tr>
 </table>

Below is a short proposal of our project so that you know what the project is all about.

I would be super excited if someone is interested and am happy about any suggestions for further analysis, etc.
In coronaviruses, packaging of the viral RNA genome into the capsid is dependent on self-assembly of the nucleocapsid protein (N-protein) and binding of the N-protein to the (~70 nt) packaging signal on the viral RNA via the RNA-binding domain of the N-protein. Using our expertise in RNA-binding proteins, RNA biology and reconstitution experiments, we would like to reconstitute Covid-19 viral capsid assembly in vitro using a non-infectious fragment of the viral genome containing the predicted packaging signal as well as purified N-protein. Given that the Covid-19 N-protein is intrinsically disordered and contains an RNA-binding domain, we predict that assembly occurs through weak multivalent interactions and the process of liquid-liquid phase separation. Subsequently, we plan to test if we can disrupt assembly through the use of small molecules or anti-sense oligos. As a proof of principal, we initially plan to use the compound 1,6 hexanediol that is known to disrupt multivalent interactions, followed by the screening of clinically approved small molecules, ideally in collaboration with UNC screening platforms. Potential candidate molecules can furthermore be tested in cell culture expressing non-infectious N-Protein and RNA Genome-fragments and results could serve to identify candidate treatment options for Covid-19. (edited) 
