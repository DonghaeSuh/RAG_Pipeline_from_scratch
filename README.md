# RAG_Pipeline_from_scratch

본 레포지토리에서는 
- RAG Pipeline을 처음부터 구현하고
- QA 데이터를 생성하여
- Retriever와 Generation를 평가할 수 있습니다.


Sparse Retriever와 Dense Retriever 모두를 사용하여 평가를 진행했고, \
이를 통해 BM25와 같은 N-gram 기반으로 유사도를 측정하는 Retriever가 금융권과 같은 문서에 대해 좋은 성능을 보이는 것을 확인했습니다.  


추가적으로, 성능 향상을 위해 Contextual Retrieval Preprocessing을 진행했고 \
이를 통해 Dense Retriever의 큰 성능 향상을 얻어낼 수 있었습니다.  
