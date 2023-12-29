# Assignment - 2 Report

Dataset we have used is the bbc-news sports dataset. We have taken 20 documents from each sports category. They are stored in inputFiles.

001-020: Cricket

021-040: Athletics

041-060: Football

061-080: Rugby

081-100: Tennis

Created two separate indexes, one that uses the whiteSpaceAnlayzer which tokenizes on whitespaces only. The other uses the EnglishAnalyzer which consists of StandardTokenizer, StandardFilter, EnglishPossessiveFilter, LowerCaseFilter, StopFilter, and PorterStemFilter. The indexes are stored in indexedFiles and indexedFilesSmart respectively.

Queries used: "cricket":, "athletics", "football", "rugby", and "tennis"
