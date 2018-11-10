---
published: true
permalink: /data-elements-alternate
layout: article
filename: data-elements-alternate.md
title: Draft Grants Management Data Elements Feedback 
page: child
---

## Give Feedback on the Federal Grants Management Data Standards 

You can provide feedback on the Federal Grants Management Draft Data Standards in four easy steps! 
1. Sign up for a [FREE GitHub Account](https://github.com/). If you already have a GitHub Account skip to Step 2.
2. Review the 426 Data Standards Elements in the table below. Use the search box in the top right corner to filter by keyword.
3. Select the “Leave Feedback” button to open a new tab and select "Get Started." Enter your comments in the box for a single data element, being sure to title that comment with the data element number. You must submit a separate comment/issue for each data element. 
4. Select “Submit New Issue” to submit your comments. Repeat the process for each data element you have feedback for. 

<a href="/assets/docs/use-case-summaries.pdf"  class="btn btn-primary">Download Github Feedback FAQs PDF</a> <a href="/assets/docs/use-case-summaries.pdf"  class="btn btn-primary">Download User Guide for Github Feedback PDF</a> 

To provide feedback on the Draft Data Elements, refer to the User Guide and FAQs. Please ensure that you reference which data element you are commenting on. All comments received may be posted without change, including any personal information provided. Do not submit confidential business information, trade secret information, or other sensitive or protected information that you do not want to be available to the public.

<a href="https://github.com/OFFM-MCAB/grantsfeedback/issues/new/choose" target="_blank" class="btn btn-primary" role="button">Leave Feedback</a>

## Draft Data Elements

<table class="element-table">
  <thead>
    <tr>
      <th scope="col">Number</th>
      <th scope="col">Element</th>
      <th scope="col">Definition</th>
    </tr>
  </thead>
  <tbody>

{% for element in site.data.grm-data-elements-v1-2 %}
    <tr id="{{ element.proposed_data_element_name }}">
        <td><a href="#{{ element.proposed_data_element_name }}"> {{ element.data_element_number }} </a></td>
        <td>  {{ element.proposed_data_element_name }} </td>
        <td>  {{ element.proposed_data_element_definition }} </td>
    </tr>
{% endfor %}

  </tbody>
</table>


Below you can download entire draft data elements list. 


<a href="/data/grm-data-elements-v1-2.csv"  class="btn btn-primary">Download Draft Data Elements List</a>
## Join the Conversation!

Do you have questions about the process for giving feedback? Call into our Office Hours 
Hosted by the Results-Oriented for Accountability Grants CAP Goal Team to ask any questions you may have. 
* November 29, Time TBD
* December 6, Time TBD
* December 13, Time TBD 


To join an Office Hour Session use the following number:
* 1-866-928-2008; 8514834# 

