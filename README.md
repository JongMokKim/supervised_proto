관련 논문 정리

1. Unsupervised Learning of Visual Features by Contrasting Cluster Assignments, https://arxiv.org/pdf/2006.09882.pdf
: 가장 baseline이 되는 fair팀 논문. prototype 관련 개념 알아야함. 깃헙 : https://github.com/facebookresearch/swav

2. Supervised Conntrastive Learnning : https://arxiv.org/pdf/2004.11362.pdf
: 제목대로 contrastive learnninng을 supervised로 풀어낸 논문. 향후 성능으로 비교해야할 듯

3. Understanding Contrastive Representation Learning through Alignment and Uniformity on the Hypersphere , https://arxiv.org/pdf/2005.10242.pdf
: conttrastive learning에서 성능을 평가할 수 있는 메트릭으로 alignment와 unnniformity를 제시. unit hypersphre 상에서 feature distribution을 최대한 퍼트려 둘수록 representation learninig이 효과적으로 진행되었음을 제시함.

4. What makes for good views for contrastive learning, https://arxiv.org/pdf/2005.10243.pdf
: conntrastive learninng에서 어떤 view(augmentation) 를 사용해야ㅑ 효과적으로 학습이 될지에 대해 고민한 논문.
view 간에 mutual information을 줄이는 방향으로 언급하며 실험적으로 성능도 올라간것을 보임
 
