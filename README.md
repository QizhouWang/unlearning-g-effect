# rethinking_unlearning

run basher1.py for the original unlearning methods with different checkpoints, automatically saving into the folder named icml.

run basher2.py for the computation of g-effects for the save checkpoints, the results can be save to a particular file. 

For example,

'''
python basher1.py ga --model=llama --cuda_id=3 --setting=forget05 --hyper=2 

python basher2.py ga --model=llama --cuda_id=3 --setting=forget05 --hyper=2 > ga_ge_log.txt
'''
