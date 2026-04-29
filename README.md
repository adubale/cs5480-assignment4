# cs5480-assignment4
Assignment Description:
In Assignment 3 you saw that deep networks fail in predictable ways — gradients vanish across layers, activations explode, and nothing trains without careful engineering. You fixed those failures one tool at a time.

This assignment runs the same playbook, but the failure now happens across time instead of across layers. You will start with a broken vanilla RNN — one that cannot learn long-range dependencies — and fix it step by step: first with attention as a soft alignment mechanism, then with the Transformer architecture that replaces recurrence entirely, and finally with BERT, which shows what happens when you scale that architecture with massive pretraining.

By the end, you will have implemented the core of modern NLP from first principles and trained it on real data. 
