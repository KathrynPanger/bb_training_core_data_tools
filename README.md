<h1>Core Data Tools: Training Notebooks for Basic Data Operations</h1>

<h2>Directory Structure</h2>
<ul>
<li>Base</li>
  <ul>
    <li>code</li>
      <ul>
        <li>clean_csv.ipynb</li>
        <li>clean_csv_extended_version.ipynb</li>
      </ul>
  <li>data</li>
    <ul>
      <li>raw</li>
        <ul>
            <li>(contains raw csv files to load into notebooks)</li>
        </ul>
    </ul>
      <li>processed</li>
        <ul>
          <li>(contains finished processed csv files, after data cleaning is complete)</li>
        </ul>
</ul>
</ul>

<h3>The Files</h3>
<p><b></bb>clean_csv.ipynb</b></p>
<p>Contains functions for:</p>
<ol>
    <li>Loading a csv</li>
    <li>Cleaning the headers</li>
    <li>Cleaning the string columns</li>
    <li>Cleaning the numeric columns</li>
    <li>Creating a deterministic "ID" column based on identifying values</li>
    <li>Writing out a clean csv</li>
    <li>Converting a csv to UTF-8 format</li>
</ol>
<p></p>
<p><b></bb>clean_csv_extended_version.ipynb</b></p>
<p>Contains all the functions described in clean_csv, plus added functions for:</p>
<ol>
    <li>Cleaning date columns</li>
    <li>Cleaning list columns</li>
    <li>Cleaning mixed-data-type columns (object format in pandas)</li>

</ol>