# The Scottish Index of Multiple Deprivation (SIMD)

Our research uses many variables provided by the Scottish Index of Multiple Deprivation (SIMD). SIMD is the Scottish Government's standard approach to identify multiple deprivation by geographical areas of Scotland. According to the government's [website](https://www.gov.scot/collections/scottish-index-of-multiple-deprivation-2020/), the index can "help improve understanding about the outcomes and circumstances of people living in the most deprived areas in Scotland".

SIMD[^simd-1] was first published in 2012, and has been updated in 2016 and 2020. The latest version (2020) was revised due to the local stakeholders' requests of corrections for the income domain results for several specific data zones.

[^simd-1]: SIMD is an area-based measure of relative deprivation: not every person in a highly deprived area will themselves be experiencing high levels of deprivation.

> SIMD ranks data zones from **1st as the most deprived** to **6976th as the least deprived**. There are quintiles, deciles, or other measures that group the ranks to certain levels.

## Name

SIMD

## Published Year

2020 Version 2

## Metadata

The table below describes the glossary of the variables mentioned in the SIMD GIS dataset.


```{=html}
<div id="sjobzbsvkr" style="overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>html {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Helvetica Neue', 'Fira Sans', 'Droid Sans', Arial, sans-serif;
}

#sjobzbsvkr .gt_table {
  display: table;
  border-collapse: collapse;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: normal;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #A8A8A8;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #A8A8A8;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}

#sjobzbsvkr .gt_heading {
  background-color: #FFFFFF;
  text-align: center;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#sjobzbsvkr .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}

#sjobzbsvkr .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 0;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}

#sjobzbsvkr .gt_bottom_border {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#sjobzbsvkr .gt_col_headings {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#sjobzbsvkr .gt_col_heading {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}

#sjobzbsvkr .gt_column_spanner_outer {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}

#sjobzbsvkr .gt_column_spanner_outer:first-child {
  padding-left: 0;
}

#sjobzbsvkr .gt_column_spanner_outer:last-child {
  padding-right: 0;
}

#sjobzbsvkr .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}

#sjobzbsvkr .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
}

#sjobzbsvkr .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: middle;
}

#sjobzbsvkr .gt_from_md > :first-child {
  margin-top: 0;
}

#sjobzbsvkr .gt_from_md > :last-child {
  margin-bottom: 0;
}

#sjobzbsvkr .gt_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  overflow-x: hidden;
}

#sjobzbsvkr .gt_stub {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
}

#sjobzbsvkr .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}

#sjobzbsvkr .gt_row_group_first td {
  border-top-width: 2px;
}

#sjobzbsvkr .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#sjobzbsvkr .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #D3D3D3;
}

#sjobzbsvkr .gt_first_summary_row.thick {
  border-top-width: 2px;
}

#sjobzbsvkr .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#sjobzbsvkr .gt_grand_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#sjobzbsvkr .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #D3D3D3;
}

#sjobzbsvkr .gt_striped {
  background-color: rgba(128, 128, 128, 0.05);
}

#sjobzbsvkr .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#sjobzbsvkr .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#sjobzbsvkr .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-left: 4px;
  padding-right: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#sjobzbsvkr .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#sjobzbsvkr .gt_sourcenote {
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#sjobzbsvkr .gt_left {
  text-align: left;
}

#sjobzbsvkr .gt_center {
  text-align: center;
}

#sjobzbsvkr .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}

#sjobzbsvkr .gt_font_normal {
  font-weight: normal;
}

#sjobzbsvkr .gt_font_bold {
  font-weight: bold;
}

#sjobzbsvkr .gt_font_italic {
  font-style: italic;
}

#sjobzbsvkr .gt_super {
  font-size: 65%;
}

#sjobzbsvkr .gt_two_val_uncert {
  display: inline-block;
  line-height: 1em;
  text-align: right;
  font-size: 60%;
  vertical-align: -0.25em;
  margin-left: 0.1em;
}

#sjobzbsvkr .gt_footnote_marks {
  font-style: italic;
  font-weight: normal;
  font-size: 75%;
  vertical-align: 0.4em;
}

#sjobzbsvkr .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}

#sjobzbsvkr .gt_slash_mark {
  font-size: 0.7em;
  line-height: 0.7em;
  vertical-align: 0.15em;
}

#sjobzbsvkr .gt_fraction_numerator {
  font-size: 0.6em;
  line-height: 0.6em;
  vertical-align: 0.45em;
}

#sjobzbsvkr .gt_fraction_denominator {
  font-size: 0.6em;
  line-height: 0.6em;
  vertical-align: -0.05em;
}
</style>
<table class="gt_table">
  <caption>(#tab:unnamed-chunk-1)SIMDv2 Glossary</caption>
  
  <thead class="gt_col_headings">
    <tr>
      <th class="gt_col_heading gt_columns_bottom_border gt_left" rowspan="1" colspan="1"><strong>Category</strong></th>
      <th class="gt_col_heading gt_columns_bottom_border gt_left" rowspan="1" colspan="1"><strong>Label</strong></th>
      <th class="gt_col_heading gt_columns_bottom_border gt_left" rowspan="1" colspan="1"><strong>Type</strong></th>
      <th class="gt_col_heading gt_columns_bottom_border gt_left" rowspan="1" colspan="1"><strong>Description</strong></th>
    </tr>
  </thead>
  <tbody class="gt_table_body">
    <tr><td class="gt_row gt_left">Geography</td>
<td class="gt_row gt_left">DataZone</td>
<td class="gt_row gt_left">Code</td>
<td class="gt_row gt_left">2011 data zone</td></tr>
    <tr><td class="gt_row gt_left">Geography</td>
<td class="gt_row gt_left">LAName</td>
<td class="gt_row gt_left">Name</td>
<td class="gt_row gt_left">Council area name</td></tr>
    <tr><td class="gt_row gt_left">Population</td>
<td class="gt_row gt_left">SAPE2017</td>
<td class="gt_row gt_left">Count</td>
<td class="gt_row gt_left">2017 NRS small area population estimates</td></tr>
    <tr><td class="gt_row gt_left">Population</td>
<td class="gt_row gt_left">WAPE2017</td>
<td class="gt_row gt_left">Count</td>
<td class="gt_row gt_left">2017 NRS small area population estimates and state pension age</td></tr>
    <tr><td class="gt_row gt_left">Overall SIMD</td>
<td class="gt_row gt_left">Rankv2</td>
<td class="gt_row gt_left">Rank</td>
<td class="gt_row gt_left">Rank</td></tr>
    <tr><td class="gt_row gt_left">Overall SIMD</td>
<td class="gt_row gt_left">Quintilev2</td>
<td class="gt_row gt_left">Quantile</td>
<td class="gt_row gt_left">Quintile</td></tr>
    <tr><td class="gt_row gt_left">Overall SIMD</td>
<td class="gt_row gt_left">Decilev2</td>
<td class="gt_row gt_left">Quantile</td>
<td class="gt_row gt_left">Decile</td></tr>
    <tr><td class="gt_row gt_left">Overall SIMD</td>
<td class="gt_row gt_left">Vigintilv2</td>
<td class="gt_row gt_left">Quantile</td>
<td class="gt_row gt_left">Vigintile</td></tr>
    <tr><td class="gt_row gt_left">Overall SIMD</td>
<td class="gt_row gt_left">Percentv2</td>
<td class="gt_row gt_left">Quantile</td>
<td class="gt_row gt_left">Percentile</td></tr>
    <tr><td class="gt_row gt_left">Income</td>
<td class="gt_row gt_left">IncRate</td>
<td class="gt_row gt_left">Percentage</td>
<td class="gt_row gt_left">Percentage of people who are income deprived</td></tr>
    <tr><td class="gt_row gt_left">Income</td>
<td class="gt_row gt_left">IncNumDep</td>
<td class="gt_row gt_left">Count</td>
<td class="gt_row gt_left">Number of people who are income deprived</td></tr>
    <tr><td class="gt_row gt_left">Income</td>
<td class="gt_row gt_left">IncRankv2</td>
<td class="gt_row gt_left">Rank</td>
<td class="gt_row gt_left">Income domain rank</td></tr>
    <tr><td class="gt_row gt_left">Employment</td>
<td class="gt_row gt_left">EmpRate</td>
<td class="gt_row gt_left">Percentage</td>
<td class="gt_row gt_left">Percentage of working age people who are employment deprived</td></tr>
    <tr><td class="gt_row gt_left">Employment</td>
<td class="gt_row gt_left">EmpNumDep</td>
<td class="gt_row gt_left">Count</td>
<td class="gt_row gt_left">Number of working age people who are employment deprived</td></tr>
    <tr><td class="gt_row gt_left">Employment</td>
<td class="gt_row gt_left">EmpRank</td>
<td class="gt_row gt_left">Rank</td>
<td class="gt_row gt_left">Employment domain rank</td></tr>
    <tr><td class="gt_row gt_left">Health</td>
<td class="gt_row gt_left">HlthCIFSR</td>
<td class="gt_row gt_left">Standardised ratio</td>
<td class="gt_row gt_left">Comparative illness factor</td></tr>
    <tr><td class="gt_row gt_left">Health</td>
<td class="gt_row gt_left">HlthAlcSR</td>
<td class="gt_row gt_left">Standardised ratio</td>
<td class="gt_row gt_left">Hospital stays related to alcohol use</td></tr>
    <tr><td class="gt_row gt_left">Health</td>
<td class="gt_row gt_left">HlthDrugSR</td>
<td class="gt_row gt_left">Standardised ratio</td>
<td class="gt_row gt_left">Hospital stays related to drug use</td></tr>
    <tr><td class="gt_row gt_left">Health</td>
<td class="gt_row gt_left">HlthSMR</td>
<td class="gt_row gt_left">Standardised ratio</td>
<td class="gt_row gt_left">Mortality</td></tr>
    <tr><td class="gt_row gt_left">Health</td>
<td class="gt_row gt_left">HlthDprsPc</td>
<td class="gt_row gt_left">Percentage</td>
<td class="gt_row gt_left">Proportion of population being prescribed drugs for anxiety, depression or psychosis</td></tr>
    <tr><td class="gt_row gt_left">Health</td>
<td class="gt_row gt_left">HlthLBWTPc</td>
<td class="gt_row gt_left">Percentage</td>
<td class="gt_row gt_left">Proportion of live singleton births of low birth weight</td></tr>
    <tr><td class="gt_row gt_left">Health</td>
<td class="gt_row gt_left">HlthEmerSR</td>
<td class="gt_row gt_left">Standardised ratio</td>
<td class="gt_row gt_left">Emergency stays in hospital</td></tr>
    <tr><td class="gt_row gt_left">Health</td>
<td class="gt_row gt_left">HlthRank</td>
<td class="gt_row gt_left">Rank</td>
<td class="gt_row gt_left">Health domain rank</td></tr>
    <tr><td class="gt_row gt_left">Education, Skills and Training</td>
<td class="gt_row gt_left">EduAttend</td>
<td class="gt_row gt_left">Percentage</td>
<td class="gt_row gt_left">School pupil attendance</td></tr>
    <tr><td class="gt_row gt_left">Education, Skills and Training</td>
<td class="gt_row gt_left">EduAttain</td>
<td class="gt_row gt_left">Score</td>
<td class="gt_row gt_left">Attainment of school leavers</td></tr>
    <tr><td class="gt_row gt_left">Education, Skills and Training</td>
<td class="gt_row gt_left">EduNoQuals</td>
<td class="gt_row gt_left">Standardised ratio</td>
<td class="gt_row gt_left">Working age people with no qualifications</td></tr>
    <tr><td class="gt_row gt_left">Education, Skills and Training</td>
<td class="gt_row gt_left">EduNotPart</td>
<td class="gt_row gt_left">Percentage</td>
<td class="gt_row gt_left">Proportion of people aged 16-19 not participating in education, employment or training</td></tr>
    <tr><td class="gt_row gt_left">Education, Skills and Training</td>
<td class="gt_row gt_left">EduUniver</td>
<td class="gt_row gt_left">Percentage</td>
<td class="gt_row gt_left">17-21 year olds entering university as a proportion of the 17-21 population</td></tr>
    <tr><td class="gt_row gt_left">Education, Skills and Training</td>
<td class="gt_row gt_left">EduRank</td>
<td class="gt_row gt_left">Rank</td>
<td class="gt_row gt_left">Education domain rank</td></tr>
    <tr><td class="gt_row gt_left">Geographic Access to Services</td>
<td class="gt_row gt_left">GAccPetrol</td>
<td class="gt_row gt_left">Time (minutes)</td>
<td class="gt_row gt_left">Average drive time to a petrol station in minutes</td></tr>
    <tr><td class="gt_row gt_left">Geographic Access to Services</td>
<td class="gt_row gt_left">GAccDTGP</td>
<td class="gt_row gt_left">Time (minutes)</td>
<td class="gt_row gt_left">Average drive time to a GP surgery in minutes</td></tr>
    <tr><td class="gt_row gt_left">Geographic Access to Services</td>
<td class="gt_row gt_left">GAccDTPost</td>
<td class="gt_row gt_left">Time (minutes)</td>
<td class="gt_row gt_left">Average drive time to a post office in minutes</td></tr>
    <tr><td class="gt_row gt_left">Geographic Access to Services</td>
<td class="gt_row gt_left">GAccDTPsch</td>
<td class="gt_row gt_left">Time (minutes)</td>
<td class="gt_row gt_left">Average drive time to a primary school in minutes</td></tr>
    <tr><td class="gt_row gt_left">Geographic Access to Services</td>
<td class="gt_row gt_left">GAccDTSsch</td>
<td class="gt_row gt_left">Time (minutes)</td>
<td class="gt_row gt_left">Average drive time to a secondary school in minutes</td></tr>
    <tr><td class="gt_row gt_left">Geographic Access to Services</td>
<td class="gt_row gt_left">GAccDTRet</td>
<td class="gt_row gt_left">Time (minutes)</td>
<td class="gt_row gt_left">Average drive time to a retail centre in minutes</td></tr>
    <tr><td class="gt_row gt_left">Geographic Access to Services</td>
<td class="gt_row gt_left">GAccPTGP</td>
<td class="gt_row gt_left">Time (minutes)</td>
<td class="gt_row gt_left">Public transport travel time to a GP surgery in minutes</td></tr>
    <tr><td class="gt_row gt_left">Geographic Access to Services</td>
<td class="gt_row gt_left">GAccPTPost</td>
<td class="gt_row gt_left">Time (minutes)</td>
<td class="gt_row gt_left">Public transport travel time to a post office in minutes</td></tr>
    <tr><td class="gt_row gt_left">Geographic Access to Services</td>
<td class="gt_row gt_left">GAccPTRet</td>
<td class="gt_row gt_left">Time (minutes)</td>
<td class="gt_row gt_left">Public transport travel time to a retail centre in minutes</td></tr>
    <tr><td class="gt_row gt_left">Geographic Access to Services</td>
<td class="gt_row gt_left">GAccBrdbnd</td>
<td class="gt_row gt_left">Percentage</td>
<td class="gt_row gt_left">Percentage of premises without access to superfast broadband (at least 30Mb/s download speed)</td></tr>
    <tr><td class="gt_row gt_left">Geographic Access to Services</td>
<td class="gt_row gt_left">GAccRank</td>
<td class="gt_row gt_left">Rank</td>
<td class="gt_row gt_left">Access domain rank</td></tr>
    <tr><td class="gt_row gt_left">Crime</td>
<td class="gt_row gt_left">CrimeCount</td>
<td class="gt_row gt_left">Count</td>
<td class="gt_row gt_left">Number of recorded crimes of violence, sexual offences, domestic housebreaking, vandalism, drugs offences, and common assault</td></tr>
    <tr><td class="gt_row gt_left">Crime</td>
<td class="gt_row gt_left">CrimeRate</td>
<td class="gt_row gt_left">Rate</td>
<td class="gt_row gt_left">Recorded crimes of violence, sexual offences, domestic housebreaking, vandalism, drugs offences, and common assault per 10,000 population</td></tr>
    <tr><td class="gt_row gt_left">Crime</td>
<td class="gt_row gt_left">CrimeRank</td>
<td class="gt_row gt_left">Rank</td>
<td class="gt_row gt_left">Crime domain rank</td></tr>
    <tr><td class="gt_row gt_left">Housing</td>
<td class="gt_row gt_left">HouseNumOC</td>
<td class="gt_row gt_left">Count</td>
<td class="gt_row gt_left">Number of people in households that are overcrowded</td></tr>
    <tr><td class="gt_row gt_left">Housing</td>
<td class="gt_row gt_left">HouseNumNC</td>
<td class="gt_row gt_left">Count</td>
<td class="gt_row gt_left">Number of people in households without central heating</td></tr>
    <tr><td class="gt_row gt_left">Housing</td>
<td class="gt_row gt_left">HouseOCrat</td>
<td class="gt_row gt_left">Percentage</td>
<td class="gt_row gt_left">Percentage of people in households that are overcrowded</td></tr>
    <tr><td class="gt_row gt_left">Housing</td>
<td class="gt_row gt_left">HouseNCrat</td>
<td class="gt_row gt_left">Percentage</td>
<td class="gt_row gt_left">Percentage of people in households without central heating</td></tr>
    <tr><td class="gt_row gt_left">Housing</td>
<td class="gt_row gt_left">HouseRank</td>
<td class="gt_row gt_left">Rank</td>
<td class="gt_row gt_left">Housing domain rank</td></tr>
  </tbody>
  
  
</table>
</div>
```

## Source

-   Detailed Description: gov.scot webiste <https://www.gov.scot/collections/scottish-index-of-multiple-deprivation-2020/>

-   Revision notice: <https://www.gov.scot/publications/scottish-index-of-multiple-deprivation-2020v2-revision-notice/>

-   Indicators: <https://www.gov.scot/publications/scottish-index-of-multiple-deprivation-2020v2-indicator-data/>

```{=html}
<!-- -->
```
-   GIS data: <https://www.spatialdata.gov.scot/geonetwork/srv/eng/catalog.search#/metadata/02866b0b-66e5-46ab-9b1c-d433dc3c2fae>
