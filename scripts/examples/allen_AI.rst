-----------------------------------
Allen_AI
-----------------------------------

Kaggle competetion entry for Allen_AI
T:\user\dev\src\python\kaggle\output

.. contents:: 


Overview
===========================================

This document contains details on the project Allen_AI

 - kaggle_url = https://www.kaggle.com/c/the-allen-ai-science-challenge

 - files_root_folder = T:\user\dev\src\python\kaggle

 - files_src_data = T:\user\dev\src\python\kaggle\data

 - files_op_folder = T:\user\dev\src\python\kaggle\output

 - date_last_ran = 2016-03-20 21:27:13


TABLES
===========================================

lookup_src.csv
-------------------------

======================== ======================== 
name                     url                      
======================== ======================== 
page-resources           http://aclweb.org/aclwiki/index.php?title=RTE_Knowledge_Resources#Publicly_available_Resources
science_notes            http://www.ck12.org/     
data-wikipedia           https://en.wikipedia.org/wiki/Wikipedia:Database_download
YAGO                     http://yago-knowledge.org
Dbpedia                  http://dbpedia.org       
Freebase                 http://freebase.com      
Entitycube               http://entitycube.research.microsoft.com
renlifang                http://renlifang.msra.cn 
NELL                     http://rtw.ml.cmu.edu    
DeepDive                 http://deepdive.stanford.edu
Probase                  http://research.microsoft.com/en-us/projects/probase/
KnowItAll                http://openie.cs.washington.edu
ReVerb                   http://reverb.cs.washington.edu
BabelNet                 http://babelnet.org      
WikiNet                  http://www.h-its.org/english/research/nlp/download/
ConceptNet               http://conceptnet5.media.mit.edu
WordNet                  http://wordnet.princeton.edu
Linked Open Data         http://linkeddata.org    
======================== ======================== 


progress.csv
-------------------------

======================== ======================== ======================== 
program                  percent                  details                  
======================== ======================== ======================== 
Source data download     100%                     download competition sample data
Allen_AI_install.py      0%                       downloads lookup data, unzips
Allen_AI_run.py          2%                       main script to run the program
method1.py               5%                       method to answer questions using heuristic #1
method2.py               0%                       method to answer questions using heuristic #2
method3.py               0%                       method to answer questions using heuristic #3
======================== ======================== ======================== 


results.csv
-------------------------

======================== ======================== ======================== ======================== ======================== 
program                  function                 param                    result                   date_ran                 
======================== ======================== ======================== ======================== ======================== 
method1.py               solve                    -0.5                     -4.25                    2016-03-20 21:27:15      
method1.py               solve                    -0.02                    -0.17                    2016-03-20 21:27:15      
method1.py               solve                    1                        8.5                      2016-03-20 21:27:15      
method1.py               solve                    124                      1054.0                   2016-03-20 21:27:15      
method2.py               solve                    -0.5                     583858482                2016-03-20 21:27:15      
method2.py               solve                    -0.02                    583858482                2016-03-20 21:27:15      
method2.py               solve                    1                        583858482                2016-03-20 21:27:15      
method2.py               solve                    124                      583858482                2016-03-20 21:27:15      
method3.py               solve                    -0.5                     -54.565                  2016-03-20 21:27:16      
method3.py               solve                    -0.02                    -54.565                  2016-03-20 21:27:16      
method3.py               solve                    1                        -54.565                  2016-03-20 21:27:16      
method3.py               solve                    124                      -54.565                  2016-03-20 21:27:16      
======================== ======================== ======================== ======================== ======================== 


