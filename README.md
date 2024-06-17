# code-gemma-7b-text-to-sql
This Repository contains a trainer notebook of code-gemma-7b on text-to-sql task.
TRAINING HYPERPARAMETERS:
- Epochs=1
- optimizer=paged_adamw_8bit
- learning_rate=0.0002
- warmup_ratio=0.05
- lr_scheduler_type=linear
- weight_decay=0.01
- max_seq_length=512
- lora_rank=128
- lora_alpha=32
- lora_dropout=0.1
