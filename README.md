# Nessus-port
1. **交互性**：使用Streamlit库，一个用于创建美观的web应用程序的Python库，允许用户通过web界面与之交互。
2. **文件上传**：用户可以通过文件上传功能上传CSV文件，这些文件应该是包含主机和端口信息的扫描数据。
3. **数据分析**：脚本读取CSV文件并分析其中的数据，提取出主机和端口的映射关系，并计算出总共有多少个独特的端口被开放。
4. **结果展示**：分析的结果以表格形式展示在web界面上，包括每个主机开放的所有端口。
5. **多文件支持**：脚本支持同时上传多个CSV文件，并能够合并分析结果，给出所有文件的总计信息。
6. **易于阅读的输出**：使用HTML标签来高亮显示关键信息，如端口号，使得输出更加直观易读。
7. **简洁的界面**：Streamlit提供了简洁的界面设计，使得用户可以轻松上传文件并查看分析结果。
8. **可移植性**：脚本使用了Python标准库和Streamlit库，这意味着它可以在任何支持Python和Streamlit的环境中运行。
9. **实时更新**：由于使用了Streamlit，用户的输入和脚本的输出都可以实时更新，不需要重新加载页面。
10. **局限性**：脚本假设CSV文件的结构是正确的，没有进行错误检查或数据验证，这在实际应用中可能是不够的。此外，它只提供了基础的分析功能，对于复杂的数据分析任务可能需要进一步的开发。


## 使用方法：
python3 写的

pip install -r requirement.txt

streamlit run 1.3.py

![image](https://github.com/tang51678/Nessus-port-/assets/80816552/e84a099c-7dff-48ac-b650-22d2ecfd0025)
![image](https://github.com/tang51678/Nessus-port-/assets/80816552/db79fe7d-ce4b-488b-bea9-7dd4f6c2588b)
![image](https://github.com/tang51678/Nessus-port-/assets/80816552/287af4e7-fbb7-462e-8da5-b58085e7a18c)
![image](https://github.com/tang51678/Nessus-port-/assets/80816552/2830481a-18bc-42ae-9431-2c8b80de88af)



## 更新日志

- v 1.1

- v1.2
- v1.3   更新时间: 2024-05-17    还在不断优化中   大师傅勿喷！！！



## 如果能帮到你解决问题，点个start吧！！！
