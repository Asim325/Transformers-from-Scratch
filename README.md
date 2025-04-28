# Transformers-from-Scratch
## 1_ Covers Encoder part of original transformer,implemented using tensorflow 
            . Include Embeddings+Positional Encoding 
            . Self-Attention, Multihead-Attention
            . FCN, Layer Normalizations and Residual Connection with dropouts regularization
            . Sigmoid for classfication in final layer

## 2_ Sequence to Sequence Transformer for Neural Machine Translation (Code from Tensorflow documents)
            . Complete Encoder Decoder Architecture
            . Cross Attention
            . Mask Multi Head Attention
            . Softmax
## 3_ Generative Pre-trained Transformer from Scratch
            . Decoder Part of Transformer from scratch(Embeddings, LayerNormalization, Masked Multihead Attention ,Gaussian Error Linear Unit(GELU), FFN, Residual Connections)
            . Text Generation withoud training GPT2-Small(124M)
            . Parameter Calculation, tying.
            . Memory Consumption
            Note the Scratch Noted Implemented from Book " **Building LLMs from Scratch by Sebatian Raschaka** "
            ### Pre-trained GPT2 model from Transformers lib,
                        . Text Generation with effect of different parameters on text output
                        . Top k, Top p, do_sample, repitition peanlity, temperature
                        ### Finetuning through prompts(few shot examples)
