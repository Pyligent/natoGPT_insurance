input_file_path /Users/taojin_m1/Git-Repo/nanoGPT/data/insurance/input.txt
44928
train has 8,035 tokens
val has 922 tokens


time python train.py \
  --dataset=insurance \--n_layer=4 \
  --n_head=4 \
  --n_embd=64 \
  --compile=False \
  --eval_iters=1 \
  --block_size=64 \
  --batch_size=8 \
  --device=mps

