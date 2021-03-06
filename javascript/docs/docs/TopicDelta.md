# NucleusApi.TopicDelta

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**dataset** | **String** | Dataset name. | 
**query** | **String** | Fulltext query, using mysql MATCH boolean query format. Example, (\&quot;word1\&quot; OR \&quot;word2\&quot;) AND (\&quot;word3\&quot; OR \&quot;word4\&quot;) | [optional] 
**custom_stop_words** | **[String]** |  | [optional] 
**num_topics** | **Number** | Number of topics to be extracted from the dataset and summarized. | [optional] 
**num_keywords** | **Number** | Number of keywords per topic that is extracted from the dataset. | [optional] 
**metadata_selection** | **Object** | JSON object specifying metadata-based queries on the dataset, of type {\&quot;metadata_field\&quot;: \&quot;selected_values\&quot;} | [optional] 
**period_0_start** | **String** | Start date for the initial-period dataset. Format: \&quot;YYYY-MM-DD HH:MM:SS\&quot;  | 
**period_0_end** | **String** | End date for the initial-period dataset. Format: \&quot;YYYY-MM-DD HH:MM:SS\&quot;  | 
**period_1_start** | **String** | Start date for the final-period dataset. Format: \&quot;YYYY-MM-DD HH:MM:SS\&quot;  | 
**period_1_end** | **String** | End date for the final-period dataset. Format: \&quot;YYYY-MM-DD HH:MM:SS\&quot;  | 
**excluded_docs** | **[String]** |  | [optional] 


