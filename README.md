<html>
<head>
	<meta http-equiv="content-type" content="text/html; charset=utf-8"/>
	<title></title>
</head>
<body lang="es-ES" dir="ltr">
<h2 class="western" style="font-variant: normal; letter-spacing: normal; font-style: normal">
<font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="3" style="font-size: 12pt"><b>Introduction</b></font></font></font></h2>
<p style="margin-bottom: 0.09in; line-height: 0.18in"><span style="font-variant: normal"><font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal">Fine
particulate matter (PM2.5) is an ambient air pollutant for which
there is strong evidence that it is harmful to human health. In the
United States, the Environmental Protection Agency (EPA) is tasked
with setting national ambient air quality standards for fine PM and
for tracking the emissions of this pollutant into the atmosphere.
Approximatly every 3 years, the EPA releases its database on
emissions of PM2.5. This database is known as the National Emissions
Inventory (NEI). You can read more information about the NEI at
the&nbsp;</span></span></span></font></font></font></span><a href="http://www.epa.gov/ttn/chief/eiinformation.html"><span style="font-variant: normal"><font color="#0367b0"><span style="text-decoration: none"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal">EPA
National Emissions Inventory web site</span></span></span></font></font></span></font></span></a><span style="font-variant: normal"><font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal">.</span></span></span></font></font></font></span></p>
<p style="margin-bottom: 0.09in; font-variant: normal; letter-spacing: normal; font-style: normal; font-weight: normal; line-height: 0.18in">
<font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt">For
each year and for each type of PM source, the NEI records how many
tons of PM2.5 were emitted from that source over the course of the
entire year. The data that you will use for this assignment are for
1999, 2002, 2005, and 2008.</font></font></font></p>
<h2 class="western" style="margin-top: 0.09in; margin-bottom: 0.09in; font-variant: normal; letter-spacing: normal; font-style: normal; line-height: 0.37in">
<font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="3" style="font-size: 12pt"><b>Data</b></font></font></font></h2>
<p style="margin-bottom: 0.09in; font-variant: normal; letter-spacing: normal; font-style: normal; font-weight: normal; line-height: 0.18in">
<font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt">The
data for this assignment are available from the course web site as a
single zip file:</font></font></font></p>
<ul>
	<li/>
<p style="margin-bottom: 0.09in; border: none; padding: 0in; line-height: 0.18in">
	<a href="https://d396qusza40orc.cloudfront.net/exdata%2Fdata%2FNEI_data.zip"><span style="font-variant: normal"><font color="#0367b0"><span style="text-decoration: none"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal">Data
	for Peer Assessment</span></span></span></font></font></span></font></span></a><span style="font-variant: normal"><font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal">&nbsp;[29Mb]</span></span></span></font></font></font></span></p>
</ul>
<p style="margin-bottom: 0.09in; font-variant: normal; letter-spacing: normal; font-style: normal; font-weight: normal; line-height: 0.18in">
<font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt">The
zip file contains two files:</font></font></font></p>
<p style="margin-bottom: 0.09in; line-height: 0.18in"><span style="font-variant: normal"><font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal">PM2.5
Emissions Data (</span></span></span></font></font></font></span><span style="display: inline-block; border: 1px solid #e1e1e8; padding: 0.02in 0.04in"><span style="font-variant: normal"><font color="#dd1144"><font face="Monaco, Menlo, Consolas, Courier New, monospace"><font size="1" style="font-size: 7pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal"><span style="background: #f7f7f9"><code class="western">summarySCC_PM25.rds</span></span></span></span></span></font></font></font></span></code><span style="font-variant: normal"><font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal">):
This file contains a data frame with all of the PM2.5 emissions data
for 1999, 2002, 2005, and 2008. For each year, the table contains
number of&nbsp;</span></span></span></font></font></font></span><span style="font-variant: normal"><font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt"><span style="letter-spacing: normal"><span style="font-style: normal"><b>tons</b></span></span></font></font></font></span><span style="font-variant: normal"><font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal">&nbsp;of
PM2.5 emitted from a specific type of source for the entire year.
Here are the first few rows.</span></span></span></font></font></font></span></p>
<pre class="western" style="margin-bottom: 0.09in; border: 1px solid #000000; padding: 0.09in; line-height: 0.18in"><span style="display: inline-block; border: none; padding: 0in"><span style="font-variant: normal"><font color="#333333"><font face="Monaco, Menlo, Consolas, Courier New, monospace"><font size="1" style="font-size: 7pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal"><span style="background: transparent"><code class="western">##     fips      SCC Pollutant Emissions  type year</span></span></span></span></span></font></font></font></span></code>
<span style="display: inline-block; border: none; padding: 0in"><span style="font-variant: normal"><font color="#333333"><font face="Monaco, Menlo, Consolas, Courier New, monospace"><font size="1" style="font-size: 7pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal"><span style="background: transparent"><code class="western">## 4  09001 10100401  PM25-PRI    15.714 POINT 1999</span></span></span></span></span></font></font></font></span></code>
<span style="display: inline-block; border: none; padding: 0in"><span style="font-variant: normal"><font color="#333333"><font face="Monaco, Menlo, Consolas, Courier New, monospace"><font size="1" style="font-size: 7pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal"><span style="background: transparent"><code class="western">## 8  09001 10100404  PM25-PRI   234.178 POINT 1999</span></span></span></span></span></font></font></font></span></code>
<span style="display: inline-block; border: none; padding: 0in"><span style="font-variant: normal"><font color="#333333"><font face="Monaco, Menlo, Consolas, Courier New, monospace"><font size="1" style="font-size: 7pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal"><span style="background: transparent"><code class="western">## 12 09001 10100501  PM25-PRI     0.128 POINT 1999</span></span></span></span></span></font></font></font></span></code>
<span style="display: inline-block; border: none; padding: 0in"><span style="font-variant: normal"><font color="#333333"><font face="Monaco, Menlo, Consolas, Courier New, monospace"><font size="1" style="font-size: 7pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal"><span style="background: transparent"><code class="western">## 16 09001 10200401  PM25-PRI     2.036 POINT 1999</span></span></span></span></span></font></font></font></span></code>
<span style="display: inline-block; border: none; padding: 0in"><span style="font-variant: normal"><font color="#333333"><font face="Monaco, Menlo, Consolas, Courier New, monospace"><font size="1" style="font-size: 7pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal"><span style="background: transparent"><code class="western">## 20 09001 10200504  PM25-PRI     0.388 POINT 1999</span></span></span></span></span></font></font></font></span></code>
<span style="display: inline-block; border: none; padding: 0in"><span style="font-variant: normal"><font color="#333333"><font face="Monaco, Menlo, Consolas, Courier New, monospace"><font size="1" style="font-size: 7pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal"><span style="background: transparent"><code class="western">## 24 09001 10200602  PM25-PRI     1.490 POINT 1999</span></span></span></span></span></font></font></font></span></code></pre>
<ul>
	<li/>
<p style="margin-bottom: 0.09in; border: none; padding: 0in; line-height: 0.18in">
	<span style="display: inline-block; border: 1px solid #e1e1e8; padding: 0.02in 0.04in"><span style="font-variant: normal"><font color="#dd1144"><font face="Monaco, Menlo, Consolas, Courier New, monospace"><font size="1" style="font-size: 7pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal"><span style="background: #f7f7f9"><code class="western">fips</span></span></span></span></span></font></font></font></span></code><span style="font-variant: normal"><font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal">:
	A five-digit number (represented as a string) indicating the U.S.
	county</span></span></span></font></font></font></span></p>
	<li/>
<p style="margin-bottom: 0.09in; border: none; padding: 0in; line-height: 0.18in">
	<span style="display: inline-block; border: 1px solid #e1e1e8; padding: 0.02in 0.04in"><span style="font-variant: normal"><font color="#dd1144"><font face="Monaco, Menlo, Consolas, Courier New, monospace"><font size="1" style="font-size: 7pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal"><span style="background: #f7f7f9"><code class="western">SCC</span></span></span></span></span></font></font></font></span></code><span style="font-variant: normal"><font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal">:
	The name of the source as indicated by a digit string (see source
	code classification table)</span></span></span></font></font></font></span></p>
	<li/>
<p style="margin-bottom: 0.09in; border: none; padding: 0in; line-height: 0.18in">
	<span style="display: inline-block; border: 1px solid #e1e1e8; padding: 0.02in 0.04in"><span style="font-variant: normal"><font color="#dd1144"><font face="Monaco, Menlo, Consolas, Courier New, monospace"><font size="1" style="font-size: 7pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal"><span style="background: #f7f7f9"><code class="western">Pollutant</span></span></span></span></span></font></font></font></span></code><span style="font-variant: normal"><font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal">:
	A string indicating the pollutant</span></span></span></font></font></font></span></p>
	<li/>
<p style="margin-bottom: 0.09in; border: none; padding: 0in; line-height: 0.18in">
	<span style="display: inline-block; border: 1px solid #e1e1e8; padding: 0.02in 0.04in"><span style="font-variant: normal"><font color="#dd1144"><font face="Monaco, Menlo, Consolas, Courier New, monospace"><font size="1" style="font-size: 7pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal"><span style="background: #f7f7f9"><code class="western">Emissions</span></span></span></span></span></font></font></font></span></code><span style="font-variant: normal"><font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal">:
	Amount of PM2.5 emitted, in tons</span></span></span></font></font></font></span></p>
	<li/>
<p style="margin-bottom: 0.09in; border: none; padding: 0in; line-height: 0.18in">
	<span style="display: inline-block; border: 1px solid #e1e1e8; padding: 0.02in 0.04in"><span style="font-variant: normal"><font color="#dd1144"><font face="Monaco, Menlo, Consolas, Courier New, monospace"><font size="1" style="font-size: 7pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal"><span style="background: #f7f7f9"><code class="western">type</span></span></span></span></span></font></font></font></span></code><span style="font-variant: normal"><font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal">:
	The type of source (point, non-point, on-road, or non-road)</span></span></span></font></font></font></span></p>
	<li/>
<p style="margin-bottom: 0.09in; border: none; padding: 0in; line-height: 0.18in">
	<span style="display: inline-block; border: 1px solid #e1e1e8; padding: 0.02in 0.04in"><span style="font-variant: normal"><font color="#dd1144"><font face="Monaco, Menlo, Consolas, Courier New, monospace"><font size="1" style="font-size: 7pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal"><span style="background: #f7f7f9"><code class="western">year</span></span></span></span></span></font></font></font></span></code><span style="font-variant: normal"><font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal">:
	The year of emissions recorded</span></span></span></font></font></font></span></p>
</ul>
<p style="margin-bottom: 0.09in; line-height: 0.18in"><span style="font-variant: normal"><font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal">Source
Classification Code Table (</span></span></span></font></font></font></span><span style="display: inline-block; border: 1px solid #e1e1e8; padding: 0.02in 0.04in"><span style="font-variant: normal"><font color="#dd1144"><font face="Monaco, Menlo, Consolas, Courier New, monospace"><font size="1" style="font-size: 7pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal"><span style="background: #f7f7f9"><code class="western">Source_Classification_Code.rds</span></span></span></span></span></font></font></font></span></code><span style="font-variant: normal"><font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal">):
This table provides a mapping from the SCC digit strings in the
Emissions table to the actual name of the PM2.5 source. The sources
are categorized in a few different ways from more general to more
specific and you may choose to explore whatever categories you think
are most useful. For example, source “10100101” is known as “Ext
Comb /Electric Gen /Anthracite Coal /Pulverized Coal”.</span></span></span></font></font></font></span></p>
<p style="margin-bottom: 0.09in; line-height: 0.18in"><span style="font-variant: normal"><font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal">You
can read each of the two files using the&nbsp;</span></span></span></font></font></font></span><span style="display: inline-block; border: 1px solid #e1e1e8; padding: 0.02in 0.04in"><span style="font-variant: normal"><font color="#dd1144"><font face="Monaco, Menlo, Consolas, Courier New, monospace"><font size="1" style="font-size: 7pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal"><span style="background: #f7f7f9"><code class="western">readRDS()</span></span></span></span></span></font></font></font></span></code><span style="font-variant: normal"><font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal">&nbsp;function
in R. For example, reading in each file can be done with the
following code:</span></span></span></font></font></font></span></p>
<pre class="western" style="margin-bottom: 0.09in; border: 1px solid #000000; padding: 0.09in; line-height: 0.18in"><span style="display: inline-block; border: none; padding: 0in"><span style="font-variant: normal"><font color="#333333"><font face="Monaco, Menlo, Consolas, Courier New, monospace"><font size="1" style="font-size: 7pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal"><span style="background: transparent"><code class="western">## This first line will likely take a few seconds. Be patient!</span></span></span></span></span></font></font></font></span></code>
<span style="display: inline-block; border: none; padding: 0in"><span style="font-variant: normal"><font color="#333333"><font face="Monaco, Menlo, Consolas, Courier New, monospace"><font size="1" style="font-size: 7pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal"><span style="background: transparent"><code class="western">NEI &lt;- readRDS(&quot;summarySCC_PM25.rds&quot;)</span></span></span></span></span></font></font></font></span></code>
<span style="display: inline-block; border: none; padding: 0in"><span style="font-variant: normal"><font color="#333333"><font face="Monaco, Menlo, Consolas, Courier New, monospace"><font size="1" style="font-size: 7pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal"><span style="background: transparent"><code class="western">SCC &lt;- readRDS(&quot;Source_Classification_Code.rds&quot;)</span></span></span></span></span></font></font></font></span></code></pre><p style="margin-bottom: 0.09in; line-height: 0.18in">
<span style="font-variant: normal"><font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal">as
long as each of those files is in your current working directory
(check by calling&nbsp;</span></span></span></font></font></font></span><span style="display: inline-block; border: 1px solid #e1e1e8; padding: 0.02in 0.04in"><span style="font-variant: normal"><font color="#dd1144"><font face="Monaco, Menlo, Consolas, Courier New, monospace"><font size="1" style="font-size: 7pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal"><span style="background: #f7f7f9"><code class="western">dir()</span></span></span></span></span></font></font></font></span></code><span style="font-variant: normal"><font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal">&nbsp;and
see if those files are in the listing).</span></span></span></font></font></font></span></p>
<h2 class="western" style="margin-top: 0.09in; margin-bottom: 0.09in; font-variant: normal; letter-spacing: normal; font-style: normal; line-height: 0.37in">
<font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="3" style="font-size: 12pt"><b>Assignment</b></font></font></font></h2>
<p style="margin-bottom: 0.09in; font-variant: normal; letter-spacing: normal; font-style: normal; font-weight: normal; line-height: 0.18in">
<font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt">The
overall goal of this assignment is to explore the National Emissions
Inventory database and see what it say about fine particulate matter
pollution in the United states over the 10-year period 1999–2008.
You may use any R package you want to support your analysis.</font></font></font></p>
<h3 class="western" style="margin-top: 0.09in; margin-bottom: 0.09in; font-variant: normal; letter-spacing: normal; font-style: normal; line-height: 0.37in">
<font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 10pt"><b>Questions</b></font></font></font></h3>
<p style="margin-bottom: 0.09in; font-variant: normal; letter-spacing: normal; font-style: normal; font-weight: normal; line-height: 0.18in">
<font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt">You
must address the following questions and tasks in your exploratory
analysis. For each question/task you will need to make a single plot.
Unless specified, you can use any plotting system in R to make your
plot.</font></font></font></p>
<ol>
	<li/>
<p style="margin-bottom: 0.09in; border: none; padding: 0in; font-variant: normal; letter-spacing: normal; font-style: normal; font-weight: normal; line-height: 0.18in">
	<font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt">Have
	total emissions from PM2.5 decreased in the United States from 1999
	to 2008? Using the&nbsp;<b>base</b>&nbsp;plotting system, make a
	plot showing the&nbsp;<i>total</i>&nbsp;PM2.5 emission from all
	sources for each of the years 1999, 2002, 2005, and 2008.</font></font></font></p>
	<li/>
<p style="margin-bottom: 0.09in; border: none; padding: 0in; line-height: 0.18in">
	<span style="font-variant: normal"><font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal">Have
	total emissions from PM2.5 decreased in the&nbsp;</span></span></span></font></font></font></span><span style="font-variant: normal"><font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt"><span style="letter-spacing: normal"><span style="font-style: normal"><b>Baltimore
	City</b></span></span></font></font></font></span><span style="font-variant: normal"><font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal">,
	Maryland (</span></span></span></font></font></font></span><span style="display: inline-block; border: 1px solid #e1e1e8; padding: 0.02in 0.04in"><span style="font-variant: normal"><font color="#dd1144"><font face="Monaco, Menlo, Consolas, Courier New, monospace"><font size="1" style="font-size: 7pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal"><span style="background: #f7f7f9"><code class="western">fips
	== &quot;24510&quot;</span></span></span></span></span></font></font></font></span></code><span style="font-variant: normal"><font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal">)
	from 1999 to 2008? Use the</span></span></span></font></font></font></span><span style="font-variant: normal"><font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt"><span style="letter-spacing: normal"><span style="font-style: normal"><b>base</b></span></span></font></font></font></span><span style="font-variant: normal"><font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal">&nbsp;plotting
	system to make a plot answering this question.</span></span></span></font></font></font></span></p>
	<li/>
<p style="margin-bottom: 0.09in; border: none; padding: 0in; line-height: 0.18in">
	<span style="font-variant: normal"><font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal">Of
	the four types of sources indicated by the&nbsp;</span></span></span></font></font></font></span><span style="display: inline-block; border: 1px solid #e1e1e8; padding: 0.02in 0.04in"><span style="font-variant: normal"><font color="#dd1144"><font face="Monaco, Menlo, Consolas, Courier New, monospace"><font size="1" style="font-size: 7pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal"><span style="background: #f7f7f9"><code class="western">type</span></span></span></span></span></font></font></font></span></code><span style="font-variant: normal"><font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal">&nbsp;(point,
	nonpoint, onroad, nonroad) variable, which of these four sources
	have seen decreases in emissions from 1999–2008 for&nbsp;</span></span></span></font></font></font></span><span style="font-variant: normal"><font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt"><span style="letter-spacing: normal"><span style="font-style: normal"><b>Baltimore
	City</b></span></span></font></font></font></span><span style="font-variant: normal"><font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal">?
	Which have seen increases in emissions from 1999–2008? Use
	the&nbsp;</span></span></span></font></font></font></span><span style="font-variant: normal"><font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt"><span style="letter-spacing: normal"><span style="font-style: normal"><b>ggplot2</b></span></span></font></font></font></span><span style="font-variant: normal"><font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal">&nbsp;plotting
	system to make a plot answer this question.</span></span></span></font></font></font></span></p>
	<li/>
<p style="margin-bottom: 0.09in; border: none; padding: 0in; font-variant: normal; letter-spacing: normal; font-style: normal; font-weight: normal; line-height: 0.18in">
	<font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt">Across
	the United States, how have emissions from coal combustion-related
	sources changed from 1999–2008?</font></font></font></p>
	<li/>
<p style="margin-bottom: 0.09in; border: none; padding: 0in; font-variant: normal; letter-spacing: normal; font-style: normal; font-weight: normal; line-height: 0.18in">
	<font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt">How
	have emissions from motor vehicle sources changed from 1999–2008
	in&nbsp;<b>Baltimore City</b>?</font></font></font></p>
	<li/>
<p style="margin-bottom: 0.09in; border: none; padding: 0in; line-height: 0.18in">
	<span style="font-variant: normal"><font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal">Compare
	emissions from motor vehicle sources in Baltimore City with
	emissions from motor vehicle sources in&nbsp;</span></span></span></font></font></font></span><span style="font-variant: normal"><font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt"><span style="letter-spacing: normal"><span style="font-style: normal"><b>Los
	Angeles County</b></span></span></font></font></font></span><span style="font-variant: normal"><font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal">,
	California (</span></span></span></font></font></font></span><span style="display: inline-block; border: 1px solid #e1e1e8; padding: 0.02in 0.04in"><span style="font-variant: normal"><font color="#dd1144"><font face="Monaco, Menlo, Consolas, Courier New, monospace"><font size="1" style="font-size: 7pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal"><span style="background: #f7f7f9"><code class="western">fips
	== &quot;06037&quot;</span></span></span></span></span></font></font></font></span></code><span style="font-variant: normal"><font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal">).
	Which city has seen greater changes over time in motor vehicle
	emissions?</span></span></span></font></font></font></span></p>
</ol>
<h3 class="western" style="margin-top: 0.09in; margin-bottom: 0.09in; font-variant: normal; letter-spacing: normal; font-style: normal; line-height: 0.37in">
<font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 10pt"><b>Making
and Submitting Plots</b></font></font></font></h3>
<p style="margin-bottom: 0.09in; font-variant: normal; letter-spacing: normal; font-style: normal; font-weight: normal; line-height: 0.18in">
<font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt">For
each plot you should</font></font></font></p>
<ul>
	<li/>
<p style="margin-bottom: 0.09in; border: none; padding: 0in; font-variant: normal; letter-spacing: normal; font-style: normal; font-weight: normal; line-height: 0.18in">
	<font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt">Construct
	the plot and save it to a&nbsp;<b>PNG file</b>.</font></font></font></p>
	<li/>
<p style="margin-bottom: 0.09in; border: none; padding: 0in; line-height: 0.18in">
	<span style="font-variant: normal"><font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal">Create
	a separate R code file (</span></span></span></font></font></font></span><span style="display: inline-block; border: 1px solid #e1e1e8; padding: 0.02in 0.04in"><span style="font-variant: normal"><font color="#dd1144"><font face="Monaco, Menlo, Consolas, Courier New, monospace"><font size="1" style="font-size: 7pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal"><span style="background: #f7f7f9"><code class="western">plot1.R</span></span></span></span></span></font></font></font></span></code><span style="font-variant: normal"><font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal">,&nbsp;</span></span></span></font></font></font></span><span style="display: inline-block; border: 1px solid #e1e1e8; padding: 0.02in 0.04in"><span style="font-variant: normal"><font color="#dd1144"><font face="Monaco, Menlo, Consolas, Courier New, monospace"><font size="1" style="font-size: 7pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal"><span style="background: #f7f7f9"><code class="western">plot2.R</span></span></span></span></span></font></font></font></span></code><span style="font-variant: normal"><font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal">,
	etc.) that constructs the corresponding plot, i.e. code in plot1.R
	constructs the plot1.png plot. Your code file should include code
	for reading the data so that the plot can be fully reproduced. You
	must also include the code that creates the PNG file. Only include
	the code for a single plot (i.e.&nbsp;</span></span></span></font></font></font></span><span style="display: inline-block; border: 1px solid #e1e1e8; padding: 0.02in 0.04in"><span style="font-variant: normal"><font color="#dd1144"><font face="Monaco, Menlo, Consolas, Courier New, monospace"><font size="1" style="font-size: 7pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal"><span style="background: #f7f7f9"><code class="western">plot1.R</span></span></span></span></span></font></font></font></span></code><span style="font-variant: normal"><font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal">&nbsp;should
	only include code for producing&nbsp;</span></span></span></font></font></font></span><span style="display: inline-block; border: 1px solid #e1e1e8; padding: 0.02in 0.04in"><span style="font-variant: normal"><font color="#dd1144"><font face="Monaco, Menlo, Consolas, Courier New, monospace"><font size="1" style="font-size: 7pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal"><span style="background: #f7f7f9"><code class="western">plot1.png</span></span></span></span></span></font></font></font></span></code><span style="font-variant: normal"><font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt"><span style="letter-spacing: normal"><span style="font-style: normal"><span style="font-weight: normal">)</span></span></span></font></font></font></span></p>
	<li/>
<p style="margin-bottom: 0.09in; border: none; padding: 0in; font-variant: normal; letter-spacing: normal; font-style: normal; font-weight: normal; line-height: 0.18in">
	<font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt">Upload
	the PNG file on the Assignment submission page</font></font></font></p>
	<li/>
<p style="margin-bottom: 0.09in; border: none; padding: 0in; font-variant: normal; letter-spacing: normal; font-style: normal; font-weight: normal; line-height: 0.18in">
	<font color="#333333"><font face="Helvetica Neue, Helvetica, Arial, sans-serif"><font size="2" style="font-size: 8pt">Copy
	and paste the R code from the corresponding R file into the text box
	at the appropriate point in the peer assessment.</font></font></font></p>
</ul>
<p style="margin-bottom: 0in; line-height: 100%"><br/>

</p>
</body>
</html>
