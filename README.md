Example of DVC pipelines.

In this project, we will see an example of how powerful is the DVC pipelines.
Dvc can run the pipelines smartly, catching the results from the nodes. The nodes are prepare_data.py, make_features.py, train.py, and evaluate.py.
If something hasn't changed in one of these nodes, it doesn't rerun that node but uses its cache.
