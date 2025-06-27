15 - Tables in HTML
The <table> element is used to display data in a structured way, like in rows and columns.

📦 Basic Table Structure
A table can contain three optional sections:

Tag Purpose

<thead>	Table header section
<tbody>	Table body (main data)
<tfoot>	Table footer (summary data)

These tags help organize the structure but are optional — the browser will still render the table even if they’re not used.

📋 Table Components

<tr> – Table Row: defines a row

<td> – Table Data: a cell containing data

<th> – Table Header Cell: bold and centered text, used for headings

✅ Example:

<table>
  <caption>Students Marks</caption>
  
  <thead>
    <tr>
      <th>First</th>
      <th>Last</th>
      <th>Marks</th>
    </tr>
  </thead>

  <tbody>
    <tr>
      <td>Sondos</td>
      <td>Alaa</td>
      <td>99</td>
    </tr>
    <tr>
      <td>Alaa</td>
      <td>Alaa</td>
      <td>98</td>
    </tr>
    <tr>
      <td>Ola</td>
      <td>Alaa</td>
      <td>77</td>
    </tr>
  </tbody>

  <tfoot>
    <tr>
      <td colspan="2">Total</td>
      <td>274</td>
    </tr>
  </tfoot>
</table>
🏷️ Additional Elements & Attributes
<caption>: Adds a title to the table (appears above the table).

<caption>Students Marks</caption>
border="1": Adds a border to table cells (⚠️ outdated and not recommended — use CSS instead).

cellpadding="4": Adds inner spacing inside each cell (also outdated, use CSS).

🔁 Merging Cells
To merge table cells, use:

colspan: Merge columns across a row

<td colspan="2">Total</td>
rowspan: Merge rows down a column

<td rowspan="2">Merged</td>
✅ Example of merged columns:

<tr>
  <td colspan="2">Total</td>
  <td>160</td>
</tr>
💡 Notes
Even if the structure is not well-organized (e.g. you don’t use <thead>), the browser will still render the table correctly.

But for accessibility, styling, and SEO, it’s highly recommended to use semantic structure properly.
