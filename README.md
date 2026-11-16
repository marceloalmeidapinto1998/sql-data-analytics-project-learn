<<<<<<< HEAD
<h4 align="left">SQL Data Analytics Project</h4>

<h6 align="left">Overview</h6>

<p><small>This repository contains the complete materials for the SQL data analytics project, including the raw data, all SQL queries used throughout the videos, and the comprehensive project roadmap.</small></p>

<p><small>In this project, you will explore a sales database step-by-step, uncover business trends, analyze customer and product segments, and build two full analytical reports.</small></p>

<p><small>To get started, open the setup guide located in the <code>00_setup</code> folder. It provides step-by-step instructions for installing SQL Server and creating the database on both Windows and Mac, along with troubleshooting steps for common errors.</small></p>

<h6 align="left">Repository Structure</h6>

<pre><small>
=======
<h3 align="left">SQL Data Analytics Project</h3>

<h5 align="left">Overview</h5>

<p>This repository contains the complete materials for the SQL data analytics project, including the raw data, all SQL queries used throughout the videos, and the comprehensive project roadmap.</p>

<p>In this project, you will explore a sales database step-by-step, uncover business trends, analyze customer and product segments, and build two full analytical reports.</p>

<p>To get started, open the setup guide located in the <code>00_setup</code> folder. It provides step-by-step instructions for installing SQL Server and creating the database on both Windows and Mac, along with troubleshooting steps for common errors.</p>

<h5 align="left">Repository Structure</h5>

<pre>
>>>>>>> a9b1ce7a7c777c2dfe372646e3ba48c0298bc81c
sql-data-analytics-project/
├── 00_setup/                        # The setup guide and one-click Docker start for Mac
├── 01_datasets/                     # The data as a backup file and as CSV files
│   ├── DataWarehouseAnalytics.bak   # The pre-built database ready for restoration
│   └── csv-files/                   # Raw CSV files to build the database manually
├── 02_docs/                         # Project roadmap and supplementary notes
└── 03_scripts/                      # SQL queries ordered sequentially matching the videos
    └── 00_init_database.sql         # Script to build the database from CSV files
<<<<<<< HEAD
</small></pre>

<h6 align="left">Database Setup</h6>

<p><small>You can set up the database using one of two methods:</small></p>

<ul>
  <li><small><strong>Restore the Backup:</strong> Restore <code>01_datasets/DataWarehouseAnalytics.bak</code> directly in SQL Server Management Studio (SSMS). Requires SQL Server 2022 or newer.</small></li>
  <li><small><strong>Run Initialization Script:</strong> Execute <code>03_scripts/00_init_database.sql</code>. Note that this script builds the database from the CSV files located at <code>C:\sql\sql-data-analytics-project\01_datasets\csv-files\</code>.</small></li>
</ul>

<h6 align="left">Project Roadmap</h6>

<p><small>The project is divided into two main parts, with scripts organized sequentially:</small></p>
=======
</pre>

<h5 align="left">Database Setup</h5>

<p>You can set up the database using one of two methods:</p>

<ul>
  <li><strong>Restore the Backup:</strong> Restore <code>01_datasets/DataWarehouseAnalytics.bak</code> directly in SQL Server Management Studio (SSMS). Requires SQL Server 2022 or newer.</li>
  <li><strong>Run Initialization Script:</strong> Execute <code>03_scripts/00_init_database.sql</code>. Note that this script builds the database from the CSV files located at <code>C:\sql\sql-data-analytics-project\01_datasets\csv-files\</code>.</li>
</ul>

<h5 align="left">Project Roadmap</h5>

<p>The project is divided into two main parts, with scripts organized sequentially:</p>

<ul>
  <li><strong>Exploratory Data Analysis (Scripts 01 to 06):</strong> Get familiar with the schema, explore tables and date ranges, calculate high-level totals, and identify top performers.</li>
  <li><strong>Advanced Analytics (Scripts 07 to 13):</strong> Dive deeper into performance trends, running totals, part-to-whole analysis, and customer/product segmentation. The project concludes with two comprehensive business reports focusing on customers and products.</li>
</ul>
>>>>>>> a9b1ce7a7c777c2dfe372646e3ba48c0298bc81c

<ul>
  <li><small><strong>Exploratory Data Analysis (Scripts 01 to 06):</strong> Get familiar with the schema, explore tables and date ranges, calculate high-level totals, and identify top performers.</small></li>
  <li><small><strong>Advanced Analytics (Scripts 07 to 13):</strong> Dive deeper into performance trends, running totals, part-to-whole analysis, and customer/product segmentation. The project concludes with two comprehensive business reports focusing on customers and products.</small></li>
</ul>