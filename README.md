# Lora for sequence classification with Roberta, Llama, and Mistral

![Thumbnail](Thumbnail.png)


1- You can find here the python script to run the models. 

2- This is an example of a command to run the script :

"~/peft_training.py  --data_path=~/processed_hf --eval_batch_size=64 --lora_alpha=64 --lora_bias=none --lora_dropout=0.07398992286835075 --lora_rank=16 --lr=0.00013709255662608955 --max_length=512 --model_name=meta-llama/Llama-2-7b-hf --num_epochs=10 --output_path=~/llama-2-7b-hf-lora-token-classification --train_batch_size=16 --weight_decay=0.005808018858604934 --set_pad_id"

3- For all the expalanations, the results and the discussion, please check the blog in HuggingFace :
