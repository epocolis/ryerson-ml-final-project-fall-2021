## Quick Start

-- conda env create -f environment.yml

Running example application:

cd seal_ogb_project

python seal_link_pred.py --dataset ogbl-ppa --num_hops 1 --use_feature --use_edge_weight --eval_steps 5 --epochs 20 --dynamic_train --dynamic_val --dynamic_test --train_percent 5 
