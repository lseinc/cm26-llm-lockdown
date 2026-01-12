# setup spikee
## follow site init instructions
## initialize env from spikee top folder
`source env/bin/activate`
## generate some data
`spikee generate --seed-folder datasets/seeds-cybersec-2025-04 --plugins 1337 --tag mytest`

## Example testing qwen2.5:3b, using 'best_of_n' dynamic attack if standard attempts fail
`spikee test --dataset datasets/cybersec-2025-04-*.jsonl --target openai_qwen25 --attack best_of_n --attack-iterations 50`

## Run test
`spikee test  --target ollama_api --target-options qwen2.5:3b --dataset datasets/lucas-simpletest.jsonl`

## Dump results
`spikee results analyze --result-file results/results_ollama_api-qwen2.5\~3b_lucas-simpletest_1768449049.jsonl  --output-format console`