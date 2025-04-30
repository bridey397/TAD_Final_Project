# Text as Data Final Project: Diversity, Equity, and Inclusion Meanings in Political Texts
Final Project Repo for Text as Data Class

## Description

This repository includes materials to analyze the meanings of the words "diversity", "equity", and "inclusion" across documents pulled from the Federal Register API to determine if the meaning of the words is consistent across groups and over time. It includes raw data, code files, clean data, figures, presentation, and report.

## Research Questions

1. What is the meaning of the words diversity, equity, and inclusion across political texts?
2. Does this meaning vary with the President in power? In this case, Trump (first term) versus Biden?
3. What are the topics of political documents that use these words?

## Repository Structure & File Contents

<table>
	<thead>
    		<tr>
	      		<th>Folder</th>
	      		<th>Folder Description</th>
			<th>Included File</th>
			<th>File Description</th>
    		</tr>
  	</thead>
  	<tbody>
    		<tr>
        		<td><tt>Clean Data</tt></td>
			<td>Includes clean data after processing </td>
			<td><tt>readme.txt</tt></td>
			<td></td>
    		</tr>
		<tr>
        		<td rowspan="2"><tt>Code</tt></td>
			<td rowspan="2">Includes all code files used to pull data from Federal Register API and create visualizations.</td>
			<td><tt>01_API.ipynb</tt></td>
			<td>Python file used to pull data from Federal Register</td>
    		</tr>
            <td><tt>02_Data_Cleaning.rmd</tt></td>
			<td>RMD file used to clean data and create visualizations from kwic, word embeddings, and LDA.</td>
    		</tr>
    		<tr>
        		<td rowspan="10"><tt>03_Replication</tt></td>
			<td rowspan="10">Includes Bartlett & Sullivan's replication materials</td>
			<td><tt>00_alc_context_exemplar.qmd</tt></td>
			<td>QMD script to replicate "Framework in Action"</td>
    		</tr>
    		<tr>
        		</td><td><tt>00_alc_context_exemplar.html</tt></td>
			<td>HTML output from running <tt>00_alc_context_exemplar.qmd</tt> script; presents code collated alongside output</td>
		</tr>
        <tr>
        		</td><td><tt>01_use_case1_group_meanings.qmd</tt></td>
			<td>QMD script to replicate framework use case 1</td>
		</tr>
        <tr>
        		</td><td><tt>01_use_case1_group_meanings.html</tt></td>
			<td>HTML output from running <tt>01_use_case1_group_meanings.qmd</tt> script; presents code collated alongside output</td>
		</tr>
        <tr>
        		</td><td><tt>02_use_case2_temporal_changes.qmd</tt></td>
			<td>QMD script to replicate framework use case 2</td>
		</tr>
        <tr>
        		</td><td><tt>02_use_case2_temporal_changes.html</tt></td>
			<td>HTML output from running <tt>02_use_case2_temporal_changes.qmd</tt> script; presents code collated alongside output</td>
		</tr>
        <tr>
        		</td><td><tt>02a_use_case2_extension.qmd</tt></td>
			<td>QMD script to execute validation</td>
		</tr>
        <tr>
        		</td><td><tt>02a_use_case2_extension.html</tt></td>
			<td>HTML output from running <tt>02a_use_case2_extension.qmd</tt> script; presents code collated alongside output</td>
		</tr>
		<tr>
        		</td><td><tt>bootstrap.css</tt></td>
			<td>CSS code called in QMD files for HTML formatting</td>
		</tr>
        <tr>
        		</td><td><tt>/_plots</tt></td>
			<td>Plots replicated from analyses; called in <tt>Bartlett-Sullivan-replication-2-presentation.qmd</tt></td>
		</tr>
  		<tr>
        		<td rowspan="5"><tt>04_Presentation</tt></td>
			<td rowspan="5">Includes presentation materials</td>
			<td><tt>Bartlett-Sullivan-replication-2-presentation.qmd</tt></td>
			<td>QMD script to produce presentation</td>
    		</tr>
    		<tr>
        		</td><td><tt>Bartlett-Sullivan-replication-2-presentation.html</tt></td>
			<td>Presentation given on 4/3/25</td>
		</tr>
        <tr>
        		</td><td><tt>semantic_shift_walkthrough.qmd</tt></td>
			<td>QMD walk-through of "Framework in action" as part of presentation (Rodriguez et al. analytic code + Bartlett, Sullivan formatting) </td>
		</tr>
        <tr>
        		</td><td><tt>semantic_shift_walkthrough.html</tt></td>
			<td>HTML output from running <tt>semantic_shift_walkthrough.qmd</tt></td>
		</tr>
		<tr>
        		</td><td><tt>bootstrap.scss</tt></td>
			<td>CSS code called in <tt>Bartlett-Sullivan-replication-2-presentation.qmd</tt> for HTML formatting in <tt>Bartlett-Sullivan-replication-2-presentation.html</tt></td>
		</tr>
  		<tr>
        		<td rowspan="2"><tt>05_FinalReport</tt></td>
			<td rowspan="2">Includes final paper materials</td>
			<td><tt>Bartlett-Sullivan-replication-2-paper.rmd</tt></td>
			<td>RMD script to produce <tt>Bartlett-Sullivan-replication-2-paper.pdf</tt></td>
    		</tr>
    		<tr>
        		</td><td><tt>Bartlett-Sullivan-replication-2-paper.pdf</tt></td>
			<td>Bartlett & Sullivan final paper</td>
		</tr>

</table>

## Author

Bridgette Sullivan

## Course & Institutional Information

This project was produced as part of the spring 2025 **PPOL 6801: Text as Data: Computational Linguistics** course at **McCourt School of Public Policy** at **Georgetown University**.

## References

