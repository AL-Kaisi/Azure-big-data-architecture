# Requirement

PART A
ABC Investment Bank Ltd wants to utilise social media and other data feeds to produce trading strategies and portfolio rebalancing decisions to give them a competitive advantage.
The Bank needs an IT solution that will inform them whether they should buy, sell or hold  a Financial Instruments. A Financial Instrument are products like Equity shares (eg Tesco share), Government Bonds (IOU issued by sovereign government eg UK Gilts), Corporate Bonds (eg IOU issued by a Corporate), 
Commodities (eg Oil, Gold) and these are traded in different Currencies and Markets globally.  Traditionally, trading strategies are devised  manually by Analysts
in the Bank's Research team. These Analyst are very expensive to employ and do not always have a great track record of detecting market trends in a timely manner. 
The Bank Business Head feels there is scope to improve how it makes such important trading decisions as it can have a significant effect on the success or failure of an institution. Not only will this information be used by the Bank to buy, sell or hold various Financial Instruments, but it will also be used in advising the Bank Clients in managing their portfolios to match their risk appetite. The Bank Clients are Pensions funds, Insurance companies, 
Hedge funds, High net individuals. The Financial Products covered are global in nature eg shares from US, like Google, Ford to UK shares eg HSBC, Next  to Indian shares eg Reliance Industries, to Australian shares eg Northern star resources , etc.
The sources of data to produce this Trading decision  will be from Social media, Market data, Online news feed, Broker notes,
Corporate data. For example, if a Company has increased mentions on Twitter its share price and market performance tends to increase. 
But this information should not be used purely in isolation and should be used in conjunction with Market data, Corporate data, etc.
The Bank's internal enterprise systems containing Corporate Data, Market Data, Broker Notes is mainly built on Relational Databases (Oracle and MS SQL Server).   
Example Data would be:
	Streaming: Click Stream, Streaming Financial product prices (from Market data vendors like Bloomberg)
	Batch: Call Detail Records 
	On-Line: Customer Sentiment 
	Unstructured: Text, Pictures, Video
The data volumes is expected to be in 100's Petabytes scale. The application needs to the highly available, scalable and accessible from the worldwide offices (London, New York, Tokyo, Hong Kong, Sydney) of ABC Investment Bank. The Trading decisions produced is confidential as it gives the Bank a significant competitive advantage.
The users of this system  will be the Bank's Traders who will buy or sell Financial Instruments on the basis of this application as well as Salesperson who will advise Clients on how best to manage their portfolio.  The Research team will also use this system to improve the quality of the work and allow them to focus on more value add details of their Analysis. Eventually, once the information and interpretation of it is proven to be of high quality, it  should be used for automatic trading by computers thereby bypassing the Traders all together.
You need to interview the Business Head of ABC Investment Bank for you to gain a detailed understanding the requirements.
Deliverables 


1/ Produce an Big Data Architecture for ABC Investment Banking providing details of  the following components in detail:  
		-Data sources, 
		- Data storage,
		- Batch processing, 
		- Real time message ingestion, 
		- Stream processing,
		- Analytical Data store 
    
    
For each of the above, discuss various options and produce your recommendation which best meets the business requirement 
								
2/  The Business Head has a limited understanding of IT and is aware of data warehouse and has suggested you build this only. Explain why you will be building a Data Lake for this solution. Discuss the approach required for implementing Data Lakes.
								
3/ The business wants near real time performance for when certain financial products  are being discussed on social media in order for it to act in a timely manner. It has been suggested the parallel distributed processing on a cluster should use  MapReduce to process this requirement. Provide a detailed assessment of whether MapReduce is  optimal to meet this  requirement and If not, what would be the best approach 
								
4/ Devise a detailed hosting strategy for this Big Data project and how this will meet the scalability, high availability requirements  for this global business. 
								
5/ Using Cloud offering from either Amazon AWS or Microsoft Azure, how would either support this Big Data project			
									      
PART B

1/ Using a tool from the Hadoop ecosystem, develop a solution to demonstrate Schema on read. How does this differ with Schema on write (Include your file(s) and code in your coursework report)
										

2/ Compare and contrast Hadoop and Relational Database system
    										           
# solution can can be found in the pdf above.
