<p> <img src="UNCiteslogo.png" width="10%" height="100%" style="display: block; margin: auto auto auto 0;" align="top"/> <img src="MIKELogo.png" width="25%" height="100%" style="display: block; margin: auto auto auto 0;" align="botom"/>   </p>

PIKE TREND ANALYSIS USING THE LEAST-SQUARES MEANS APPROACH IN R
================
CITES MIKE PROGRAMME – CENTRAL COORDINATION UNIT (CCU) <br/>
August 1, 2019
   
**R SCRIPT FOR ANALYSIS OF MIKE DATA FOR REPORTING TO CITES**

This repository contains R script for analyse of data from the [Monitoring the Illegal Killing of Elephants (MIKE) Programme](https://www.cites.org/eng/prog/mike/index.php) to produce outputs for reports to the [Convention for International Trade in Endangered Species of Wild Fauna and Flora (CITES)]( https://cites.org/eng).

The MIKE Programme is a site-based system designed to monitor trends in the illegal killing of elephants, build management capacity and provide information to help range States make appropriate management and enforcement decisions. MIKE evaluates relative poaching levels based on the Proportion of Illegally Killed Elephants (PIKE), which is calculated as the number of illegally killed elephants found divided by the total number of elephant carcasses encountered, aggregated by site and across year.

PIKE trend analysis is modelled using least-squares means (LSMEANS) approach and is detailed in the R Markdown document: [190801_PIKETrendUsingLSMEANS.Rmd](https://github.com/CITES-MIKE/MIKE-LSMEANS/blob/master/RCODE/190801_PIKETrendUsingLSMEANS.Rmd), under the subdirectory [RCODE](https://github.com/CITES-MIKE/MIKE-LSMEANS/tree/master/RCODE). The R markdown document contains embedded R code for continental-wide  PIKE trend analysis for Africa and Asia plus, at the  subregional level,  for Central, West, East and Southern Africa.  In addition the document has information about the MIKE programme, MIKE data set, and the PIKE indicator.  A sample report generated from the  R markdown document is stored in a  PDF file [190801_PIKETrendUsingLSMEANS.pdf](https://github.com/CITES-MIKE/MIKE-LSMEANS/blob/master/190801_PIKETrendUsingLSMEANS.pdf).

The analytical approach documented here has been used for the PIKE trend analysis in the reports to the two previous meetings of the Conference of the Parties (CoP16, Bangkok, 2013 in document CoP16 Doc. 53.1 and CoP17, Johannesburg, 2016, in document CoP17Doc. 57.5), and to meetings of the Standing Committee (SC62, Geneva, July 2012, in document SC62 Doc. 46.1 (Rev. 1), SC65, Geneva, July 2014, in document SC65 Doc. 42.1, SC66, Geneva, January 2016, in document SC66 Doc. 47.1 , SC69, Geneva, November 2017, in document SC69 Doc. 51.1 and SC70, Sochi, October 2018, in document SC70 Doc. 49.1).

<img src="EUFlagwithText2.png" width="20%" height="20%" style="display: block; margin: auto auto auto 0;" align="center"/>
