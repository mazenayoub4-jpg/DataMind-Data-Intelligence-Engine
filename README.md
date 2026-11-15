# DataMind-Data-Intelligence-Engine
Multi-agent ingestion and star-schema engine that turns messy CSV, Excel, and JSON files into a clean, query-ready model. Online Retail dataset (Kaggle), cleaned with Python/Spark, modeled as a star schema, with a Power BI dashboard and RAG layer.
Time
#
Log Message
15.8s	1	<class 'pandas.core.frame.DataFrame'>
15.8s	2	Index: 406829 entries, 0 to 541908
15.8s	3	Data columns (total 8 columns):
15.8s	4	 #   Column       Non-Null Count   Dtype  
15.8s	5	---  ------       --------------   -----  
15.8s	6	 0   InvoiceNo    406829 non-null  object 
15.8s	7	 1   StockCode    406829 non-null  object 
15.8s	8	 2   Description  406829 non-null  object 
15.8s	9	 3   Quantity     406829 non-null  int64  
15.8s	10	 4   InvoiceDate  406829 non-null  object 
15.8s	11	 5   UnitPrice    406829 non-null  float64
15.8s	12	 6   CustomerID   406829 non-null  float64
15.8s	13	 7   Country      406829 non-null  object 
15.8s	14	dtypes: float64(2), int64(1), object(5)
15.8s	15	memory usage: 27.9+ MB
16.5s	16	<class 'pandas.core.frame.DataFrame'>
16.5s	17	Index: 406829 entries, 0 to 541908
16.5s	18	Data columns (total 8 columns):
16.5s	19	 #   Column       Non-Null Count   Dtype         
16.5s	20	---  ------       --------------   -----         
16.5s	21	 0   InvoiceNo    406829 non-null  object        
16.5s	22	 1   StockCode    406829 non-null  object        
16.5s	23	 2   Description  406829 non-null  object        
16.5s	24	 3   Quantity     406829 non-null  int64         
16.5s	25	 4   InvoiceDate  406829 non-null  datetime64[ns]
16.5s	26	 5   UnitPrice    406829 non-null  float64       
16.5s	27	 6   CustomerID   406829 non-null  float64       
16.5s	28	 7   Country      406829 non-null  object        
16.5s	29	dtypes: datetime64[ns](1), float64(2), int64(1), object(4)
16.5s	30	memory usage: 27.9+ MB
62.7s	31	[[13647     4     4     0     0]
62.7s	32	 [    4  6100     2     1     1]
62.7s	33	 [   11     3 15708     4     2]
62.7s	34	 [    9     4     8 14709     0]
62.7s	35	 [    7     1     5     2  9825]]
62.7s	36	0.9988012187609264
63.1s	37	              precision    recall  f1-score   support
63.1s	38	
63.1s	39	           0       1.00      1.00      1.00     13678
63.1s	40	           1       1.00      1.00      1.00      6112
63.1s	41	           2       1.00      1.00      1.00     15727
63.1s	42	           3       1.00      1.00      1.00     14716
63.1s	43	           4       1.00      1.00      1.00      9828
63.1s	44	
63.1s	45	    accuracy                           1.00     60061
63.1s	46	   macro avg       1.00      1.00      1.00     60061
63.1s	47	weighted avg       1.00      1.00      1.00     60061
63.1s	48	
65.6s	49	              precision    recall  f1-score   support
65.6s	50	
65.6s	51	           0       0.99      0.99      0.99     13678
65.6s	52	           1       0.99      0.99      0.99      6112
65.6s	53	           2       0.99      0.99      0.99     15727
65.6s	54	           3       0.99      0.99      0.99     14716
65.6s	55	           4       0.99      0.99      0.99      9828
65.6s	56	
65.6s	57	    accuracy                           0.99     60061
65.6s	58	   macro avg       0.99      0.99      0.99     60061
65.6s	59	weighted avg       0.99      0.99      0.99     60061
65.6s	60	
104.7s	61	              precision    recall  f1-score   support
104.7s	62	
104.7s	63	           0       0.99      0.99      0.99     13656
104.7s	64	           1       0.99      1.00      1.00      6107
104.7s	65	           2       1.00      0.99      0.99     15756
104.7s	66	           3       0.99      1.00      0.99     14695
104.7s	67	           4       0.99      0.99      0.99      9847
104.7s	68	
104.7s	69	    accuracy                           0.99     60061
104.7s	70	   macro avg       0.99      0.99      0.99     60061
104.7s	71	weighted avg       0.99      0.99      0.99     60061
104.7s	72	
160.0s	73	/opt/conda/lib/python3.10/site-packages/traitlets/traitlets.py:2930: FutureWarning: --Exporter.preprocessors=["remove_papermill_header.RemovePapermillHeader"] for containers is deprecated in traitlets 5.0. You can pass `--Exporter.preprocessors item` ... multiple times to add items to a list.
160.0s	74	  warn(
160.0s	75	[NbConvertApp] WARNING | Config option `kernel_spec_manager_class` not recognized by `NbConvertApp`.
160.1s	76	[NbConvertApp] Converting notebook __notebook__.ipynb to notebook
160.8s	77	[NbConvertApp] Writing 575732 bytes to __notebook__.ipynb
162.9s	78	/opt/conda/lib/python3.10/site-packages/traitlets/traitlets.py:2930: FutureWarning: --Exporter.preprocessors=["nbconvert.preprocessors.ExtractOutputPreprocessor"] for containers is deprecated in traitlets 5.0. You can pass `--Exporter.preprocessors item` ... multiple times to add items to a list.
162.9s	79	  warn(
162.9s	80	[NbConvertApp] WARNING | Config option `kernel_spec_manager_class` not recognized by `NbConvertApp`.
162.9s	81	[NbConvertApp] Converting notebook __notebook__.ipynb to html
164.4s	82	[NbConvertApp] Support files will be in __results___files/
164.4s	83	[NbConvertApp] Making directory __results___files
164.4s	84	[NbConvertApp] Making directory __results___files
164.4s	85	[NbConvertApp] Making directory __results___files
164.4s	86	[NbConvertApp] Making directory __results___files
164.4s	87	[NbConvertApp] Making directory __results___files
164.4s	88	[NbConvertApp] Making directory __results___files
164.4s	89	[NbConvertApp] Making directory __results___files
164.4s	90	[NbConvertApp] Making directory __results___files
164.4s	91	[NbConvertApp] Making directory __results___files
164.4s	92	[NbConvertApp] Making directory __results___files
164.4s	93	[NbConvertApp] Writing 418198 bytes to __results__.html
