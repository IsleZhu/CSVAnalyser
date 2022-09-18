# CSV-Analyser

Welcome to Group 7's repository for 22 fall Software Engineering homework 2 & 3!

This repository is intended to read a CSV file and generate summaries of both numeric and symbolic columns, that is, medians and standard deviation for numeric columns, and mode and entropy for symbolic columns.

<!-- Pytest Coverage Comment:Begin -->
<a href="https://github.com/yzhu27/CSVAnalyser/blob/main/README.md"><img alt="Coverage" src="https://img.shields.io/badge/Coverage-90%25-brightgreen.svg" /></a><details><summary>Coverage Report </summary><table><tr><th>File</th><th>Stmts</th><th>Miss</th><th>Cover</th><th>Missing</th></tr><tbody><tr><td colspan="5"><b>src</b></td></tr><tr><td>&nbsp; &nbsp;<a href="https://github.com/yzhu27/CSVAnalyser/blob/main/src/Cols.py">Cols.py</a></td><td>20</td><td>1</td><td>1</td><td><a href="https://github.com/yzhu27/CSVAnalyser/blob/main/src/Cols.py#L 95%"> 95%</a></td></tr><tr><td>&nbsp; &nbsp;<a href="https://github.com/yzhu27/CSVAnalyser/blob/main/src/Data.py">Data.py</a></td><td>30</td><td>2</td><td>2</td><td><a href="https://github.com/yzhu27/CSVAnalyser/blob/main/src/Data.py#L 93%"> 93%</a></td></tr><tr><td>&nbsp; &nbsp;<a href="https://github.com/yzhu27/CSVAnalyser/blob/main/src/Num.py">Num.py</a></td><td>53</td><td>0</td><td>100%</td><td>&nbsp;</td></tr><tr><td>&nbsp; &nbsp;<a href="https://github.com/yzhu27/CSVAnalyser/blob/main/src/Row.py">Row.py</a></td><td>6</td><td>0</td><td>100%</td><td>&nbsp;</td></tr><tr><td>&nbsp; &nbsp;<a href="https://github.com/yzhu27/CSVAnalyser/blob/main/src/Sym.py">Sym.py</a></td><td>27</td><td>0</td><td>100%</td><td>&nbsp;</td></tr><tr><td>&nbsp; &nbsp;<a href="https://github.com/yzhu27/CSVAnalyser/blob/main/src/__init__.py">__init__.py</a></td><td>0</td><td>0</td><td>100%</td><td>&nbsp;</td></tr><tr><td>&nbsp; &nbsp;<a href="https://github.com/yzhu27/CSVAnalyser/blob/main/src/csv.py">csv.py</a></td><td>13</td><td>0</td><td>100%</td><td>&nbsp;</td></tr><tr><td>&nbsp; &nbsp;<a href="https://github.com/yzhu27/CSVAnalyser/blob/main/src/the.py">the.py</a></td><td>13</td><td>0</td><td>100%</td><td>&nbsp;</td></tr><tr><td>&nbsp; &nbsp;<a href="https://github.com/yzhu27/CSVAnalyser/blob/main/src/utils.py">utils.py</a></td><td>53</td><td>19</td><td>19</td><td><a href="https://github.com/yzhu27/CSVAnalyser/blob/main/src/utils.py#L 64%"> 64%</a></td></tr><tr><td><b>TOTAL</b></td><td><b>215</b></td><td><b>22</b></td><td><b>90%</b></td><td>&nbsp;</td></tr></tbody></table></details>
"<a href="https://github.com/yzhu27/CSVAnalyser/blob/c58abdae729b934c151b8829f95520ea5359b532/README.md"><img alt="Coverage" src="https://img.shields.io/badge/Coverage-90%25-brightgreen.svg" /></a><details><summary>Coverage Report </summary><table><tr><th>File</th><th>Stmts</th><th>Miss</th><th>Cover</th><th>Missing</th></tr><tbody><tr><td colspan="5"><b>src</b></td></tr><tr><td>&nbsp; &nbsp;<a href="https://github.com/yzhu27/CSVAnalyser/blob/c58abdae729b934c151b8829f95520ea5359b532/src/Cols.py">Cols.py</a></td><td>20</td><td>1</td><td>1</td><td><a href="https://github.com/yzhu27/CSVAnalyser/blob/c58abdae729b934c151b8829f95520ea5359b532/src/Cols.py#L 95%"> 95%</a></td></tr><tr><td>&nbsp; &nbsp;<a href="https://github.com/yzhu27/CSVAnalyser/blob/c58abdae729b934c151b8829f95520ea5359b532/src/Data.py">Data.py</a></td><td>30</td><td>2</td><td>2</td><td><a href="https://github.com/yzhu27/CSVAnalyser/blob/c58abdae729b934c151b8829f95520ea5359b532/src/Data.py#L 93%"> 93%</a></td></tr><tr><td>&nbsp; &nbsp;<a href="https://github.com/yzhu27/CSVAnalyser/blob/c58abdae729b934c151b8829f95520ea5359b532/src/Num.py">Num.py</a></td><td>53</td><td>0</td><td>100%</td><td>&nbsp;</td></tr><tr><td>&nbsp; &nbsp;<a href="https://github.com/yzhu27/CSVAnalyser/blob/c58abdae729b934c151b8829f95520ea5359b532/src/Row.py">Row.py</a></td><td>6</td><td>0</td><td>100%</td><td>&nbsp;</td></tr><tr><td>&nbsp; &nbsp;<a href="https://github.com/yzhu27/CSVAnalyser/blob/c58abdae729b934c151b8829f95520ea5359b532/src/Sym.py">Sym.py</a></td><td>27</td><td>0</td><td>100%</td><td>&nbsp;</td></tr><tr><td>&nbsp; &nbsp;<a href="https://github.com/yzhu27/CSVAnalyser/blob/c58abdae729b934c151b8829f95520ea5359b532/src/\_\_init\_\_.py">\_\_init\_\_.py</a></td><td>0</td><td>0</td><td>100%</td><td>&nbsp;</td></tr><tr><td>&nbsp; &nbsp;<a href="https://github.com/yzhu27/CSVAnalyser/blob/c58abdae729b934c151b8829f95520ea5359b532/src/csv.py">csv.py</a></td><td>13</td><td>0</td><td>100%</td><td>&nbsp;</td></tr><tr><td>&nbsp; &nbsp;<a href="https://github.com/yzhu27/CSVAnalyser/blob/c58abdae729b934c151b8829f95520ea5359b532/src/the.py">the.py</a></td><td>13</td><td>0</td><td>100%</td><td>&nbsp;</td></tr><tr><td>&nbsp; &nbsp;<a href="https://github.com/yzhu27/CSVAnalyser/blob/c58abdae729b934c151b8829f95520ea5359b532/src/utils.py">utils.py</a></td><td>53</td><td>19</td><td>19</td><td><a href="https://github.com/yzhu27/CSVAnalyser/blob/c58abdae729b934c151b8829f95520ea5359b532/src/utils.py#L 64%"> 64%</a></td></tr><tr><td><b>TOTAL</b></td><td><b>215</b></td><td><b>22</b></td><td><b>90%</b></td><td>&nbsp;</td></tr></tbody></table></details>

"
<!-- Pytest Coverage Comment:End -->
