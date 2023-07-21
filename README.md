Consider the following setting
- Total no of tokens - 12
- Base document type has 2 high probability token 
- Each document type has one more high probability token, which is unique for the document type

  ![plot](plots/doc_type_prob_distr.png)

  Now we consider a gpt model with 64 dimension and different layers and heads, trained using ADAMW optimizer

  - 1-head 1-layer, training-loss 1.740
  - document accuracy for 5 generated runs


|  seed |  accuracy  |
| ----  | ---------  |
| 0 | 82 |
| 1 | 83 |
| 2 | 83 |
| 3 | 85.5 |
| 4 |  83.5 |

- Attention and Logits distribution
## Attention head
 ![plot](plots/attention_distribution_doc_type_1.png)
 ![plot](plots/attention_distribution_doc_type_2.png)
 ![plot](plots/attention_distribution_doc_type_3.png)
 ![plot](plots/attention_distribution_doc_type_4.png)
 ![plot](plots/attention_distribution_doc_type_5.png)
 ![plot](plots/attention_distribution_doc_type_6.png)
 ![plot](plots/attention_distribution_doc_type_7.png)
 ![plot](plots/attention_distribution_doc_type_8.png)
 ![plot](plots/attention_distribution_doc_type_9.png)
 ![plot](plots/attention_distribution_doc_type_10.png)

 ## Logits distribution

 ![plot](plots/token_distribution_doc_type_1.png)
 ![plot](plots/token_distribution_doc_type_2.png)
 ![plot](plots/token_distribution_doc_type_3.png)
 ![plot](plots/token_distribution_doc_type_4.png)
 ![plot](plots/token_distribution_doc_type_5.png)
 ![plot](plots/token_distribution_doc_type_6.png)
 ![plot](plots/token_distribution_doc_type_7.png)
 ![plot](plots/token_distribution_doc_type_8.png)
 ![plot](plots/token_distribution_doc_type_9.png)
 ![plot](plots/token_distribution_doc_type_10.png)


 

  - 2-head 1-layer, training-loss 1.737

  - document accuracy for 5 generated runs


|  seed |  accuracy  |
| ----  | ---------  |
| 0 |  83.5 |
| 1 | 85   |
| 2 | 81.5 |
| 3 | 86  |
| 4 |  85.5 |

## Attention head
 ![plot](plots/h4/attention_distribution_doc_type_1.png)
 ![plot](plots/h4/attention_distribution_doc_type_2.png)
 ![plot](plots/h4/attention_distribution_doc_type_3.png)
 ![plot](plots/h4/attention_distribution_doc_type_4.png)
 ![plot](plots/h4/attention_distribution_doc_type_5.png)
 ![plot](plots/h4/attention_distribution_doc_type_6.png)
 ![plot](plots/h4/attention_distribution_doc_type_7.png)
 ![plot](plots/h4/attention_distribution_doc_type_8.png)
 ![plot](plots/h4/attention_distribution_doc_type_9.png)
 ![plot](plots/h4/attention_distribution_doc_type_10.png)

 ## Logits distribution

 ![plot](plots/h4/token_distribution_doc_type_1.png)
 ![plot](plots/h4/token_distribution_doc_type_2.png)
 ![plot](plots/h4/token_distribution_doc_type_3.png)
 ![plot](plots/h4/token_distribution_doc_type_4.png)
 ![plot](plots/h4/token_distribution_doc_type_5.png)
 ![plot](plots/h4/token_distribution_doc_type_6.png)
 ![plot](plots/h4/token_distribution_doc_type_7.png)
 ![plot](plots/h4/token_distribution_doc_type_8.png)
 ![plot](plots/h4/token_distribution_doc_type_9.png)
 ![plot](plots/h4token_distribution_doc_type_10.png)


 

  

  
