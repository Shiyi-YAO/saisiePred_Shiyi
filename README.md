Modèle de la saisie prédictible du portable (SMS)
  
Ce projet implémente deux prédictions de texte courantes basées sur Python :
    
    1. Complétion de mots (Trie)
    
    2. Prédiction du mot suivant le plus élevé (N-gram)

Structure du modèle
├── models/  
│   ├── __pycache__/  
│   ├── ngram.py             # n-gram 模型实现  
│   ├── trie.py              # Trie 树实现  
│   └── 88milSMS_88522.xlsx  # 原始 SMS 数据  
├── interface.py             # 交互式命令行界面  
├── main.py                  # 主入口脚本  
├── utils.py                 # 工具函数（数据加载、预处理等）  
├── ngram_test.py            # n-gram 单元测试  
├── trie_test.py             # Trie 单元测试  
└── README.md                # 项目说明（本文件）
