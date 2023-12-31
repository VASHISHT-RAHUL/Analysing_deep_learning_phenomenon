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


 

  - 4-heads 1-layer, training-loss 1.740

  - document accuracy for 5 generated runs


|  seed |  accuracy  |
| ----  | ---------  |
| 0 |  85.5 |
| 1 | 86   |
| 2 | 82.5 |
| 3 | 84.5  |
| 4 |  84 |

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
 ![plot](plots/h4/token_distribution_doc_type_10.png)



  - 8-heads 1-layer, training-loss 1.741

  - document accuracy for 5 generated runs


|  seed |  accuracy  |
| ----  | ---------  |
| 0 |  82 |
| 1 | 84   |
| 2 | 82 |
| 3 | 84.5  |
| 4 |  83.5 |

## Attention head
 ![plot](plots/h8/attention_distribution_doc_type_1.png)
 ![plot](plots/h8/attention_distribution_doc_type_2.png)
 ![plot](plots/h8/attention_distribution_doc_type_3.png)
 ![plot](plots/h8/attention_distribution_doc_type_4.png)
 ![plot](plots/h8/attention_distribution_doc_type_5.png)
 ![plot](plots/h8/attention_distribution_doc_type_6.png)
 ![plot](plots/h8/attention_distribution_doc_type_7.png)
 ![plot](plots/h8/attention_distribution_doc_type_8.png)
 ![plot](plots/h8/attention_distribution_doc_type_9.png)
 ![plot](plots/h8/attention_distribution_doc_type_10.png)

 ## Logits distribution

 ![plot](plots/h8/token_distribution_doc_type_1.png)
 ![plot](plots/h8/token_distribution_doc_type_2.png)
 ![plot](plots/h8/token_distribution_doc_type_3.png)
 ![plot](plots/h8/token_distribution_doc_type_4.png)
 ![plot](plots/h8/token_distribution_doc_type_5.png)
 ![plot](plots/h8/token_distribution_doc_type_6.png)
 ![plot](plots/h8/token_distribution_doc_type_7.png)
 ![plot](plots/h8/token_distribution_doc_type_8.png)
 ![plot](plots/h8/token_distribution_doc_type_9.png)
 ![plot](plots/h8/token_distribution_doc_type_10.png)

 

  

  
