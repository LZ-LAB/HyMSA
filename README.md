# The HyMSA Model
This paper has been submitted to the IEEE ICDE 2025.



## Requirements
The version of Python and major packages needed to run the code:
   
    -- python 3.9.16
    -- torch 1.12.0
    -- numpy 1.26.0
    -- tqdm 4.65.0



## How to Run

### HyMSA

#### 1. Mixed Arity Knowledge Hypergraph
```
## JF17K dataset
python main-JF.py --dataset JF17K --batch_size 128 --lr 0.1 --dr 0.1 --input_drop 0.1 --hidden_drop 0.1 --feature_drop 0.1 --k_size 1 --k_sizeN 2 --dil_size 2 --dil_sizeN 2

## WikiPeople dataset
python main-WP.py --dataset WikiPeople --batch_size 128 --lr 0.1 --dr 0.1 --input_drop 0.1 --hidden_drop 0.1 --feature_drop 0.1 --k_size 1 --k_sizeN 2 --dil_size 2 --dil_sizeN 2

## FB-AUTO dataset
python main-FB.py --dataset FB-AUTO --batch_size 128 --lr 0.1 --dr 0.1 --input_drop 0.1 --hidden_drop 0.1 --feature_drop 0.1 --k_size 1 --k_sizeN 2 --dil_size 2 --dil_sizeN 2

## M-FB15K dataset
python main-MK.py --dataset M-FB15K --batch_size 128 --lr 0.1 --dr 0.1 --input_drop 0.1 --hidden_drop 0.1 --feature_drop 0.1 --k_size 1 --k_sizeN 2 --dil_size 2 --dil_sizeN 2
```



#### 2. Fixed Arity Knowledge Hypergraph
```
## JF17K-3 dataset
python main-fixed3.py --dataset JF17K-3 --batch_size 128 --lr 0.1 --dr 0.1 --input_drop 0.1 --hidden_drop 0.1 --feature_drop 0.1 --k_size 1 --k_sizeN 2 --dil_size 2 --dil_sizeN 2

## JF17K-4 dataset
python main-fixed4.py --dataset JF17K-4 --batch_size 128 --lr 0.1 --dr 0.1 --input_drop 0.1 --hidden_drop 0.1 --feature_drop 0.1 --k_size 1 --k_sizeN 2 --dil_size 2 --dil_sizeN 2

## WikiPeople-3 dataset
python main-fixed3.py --dataset WikiPeople-3 --batch_size 128 --lr 0.1 --dr 0.1 --input_drop 0.1 --hidden_drop 0.1 --feature_drop 0.1 --k_size 1 --k_sizeN 2 --dil_size 2 --dil_sizeN 2

## WikiPeople-4 dataset
python main-fixed4.py --dataset WikiPeople-4 --batch_size 128 --lr 0.1 --dr 0.1 --input_drop 0.1 --hidden_drop 0.1 --feature_drop 0.1 --k_size 1 --k_sizeN 2 --dil_size 2 --dil_sizeN 2
```








## Acknowledgments
We are very grateful for all open-source baseline models:

1. HypE/HSimplE: https://github.com/ElementAI/HypE
2. HyperMLN: https://github.com/zirui-chen/HyperMLN
3. RAM: https://github.com/liuyuaa/RAM
4. GETD: https://github.com/liuyuaa/GETD
5. tNaLP+: https://github.com/gsp2014/NaLP
6. PosKHG: https://github.com/zirui-chen/PosKHG
7. HyConvE: https://github.com/CarllllWang/HyConvE/tree/master
8. RD-MPNN: https://github.com/ooCher/RD-MPNN/tree/main/RD_MPNN
9. ReAlE: https://github.com/baharefatemi/ReAlE
