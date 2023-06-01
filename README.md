# Study & Seminar resources

Archive repository for study & Seminar PPT and resources.

---

# Category

1. [Pytorch](#pytorch)  
    1. [Distributed training](#distributed-training)
2. [NVIDIA CUDA](#nvidia-cuda)  
3. [GNN](#gnn)  
4. [LLM](#llm)  


## Pytorch <a id="pytorch"></a>

Pytorch internal implementation or case study on pytorch models.

1. TensorPipe
    
    : Explain [Tensorpipe](https://github.com/pytorch/tensorpipe) communication backend for pytorch. 
    
2. Profiling and analyzing GraphSaint with MH-Aug
    
    : Case study on profiling implementation of GraphSaint combined with [MH-Aug](https://arxiv.org/abs/2203.14082). 
    

### Distributed training <a id="distributed-training"></a>

Pytorch distributed and parallel training. 

e.g. DDP, FSDP

1. PyTorch Distributed and Parallel Training - 1
    
    : Explain distributed training and communication strategies on pytroch and the mechanism of DDP (DistributedDataParallel).
    
2. PyTorch Distributed and Parallel Training - 2
    
    : Explain the mechanism of FSDP (Fully Sharded Data Parallel).
    
3. PyTorch Distributed and Parallel Training - 3
    
    : Explain the mechanism of RPC-based distributed training paradigms and underlying pytorch distributed Autograd engine. 
    

## NVIDIA CUDA <a id="nvidia-cuda"></a>

NVIDIA frameworks (e.g. DALI or RAPIDS Data science pipeline) and CUDA

1. Customize PyTorch memory allocation strategy and introduction to CUDA Stream-ordered Memory Allocator
    
    : Explain briefly about CUDA Stream and CUDA Stream-ordered Memory allocator and research how to implement custom pytorch memory allocator. 
    
2. Implement Graph-specific PyTorch Dataloader using DALI and cuGraph
    
    : Short brief about NVIDIA DALI and RAPIDS cuGraph and propose cuGraph-compatible DALI operator. 
    

## GNN <a id="gnn"></a>

GNN and related pipeline strategies and frameworks (e.g. DGL or Pytorch Geometric)

1. [20230329 PHW] DistDGL_ Distributed Graph Neural Network Training for Billion-Scale Graphs
    
    : Review [DistDGL](https://arxiv.org/abs/2010.05337) paper.
    

## LLM <a id="llm"></a>

LLM and finetuning applications (e.g. Standford Alpaca or Graphix-T5)

1. Graphix-T5_ Mixing Pre-Trained Transformers with Graph-Aware Layers for Text-to-SQL Parsing initial proposal
    
    : Review of [Graphix-T5](https://arxiv.org/abs/2301.07507) paper and propose a further fine-tuning strategy based on LLM (Standford Alpaca).