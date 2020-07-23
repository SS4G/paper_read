# welcome to paper reading
![img](https://avatars0.githubusercontent.com/u/16485399?s=400&u=7fdb811cbb605695545b366128bb663a3d72b6bf&v=4)
## papers in reading
* [x] YoutubeDNN `Deep Neural Networks for YouTube Recommendations.pdf`
* [x] Item CF `Amazon.com Recommendations Item-to-Item Collaborative Filtering.pdf`
* [x] FM `Factorization Machines.pdf` 
* [x] FFM `Field-aware Factorization Machines for CTR Prediction`
* [ ] LS-PLM `Learning Piece-wise Linear Models from Large Scale Data for Ad Click Prediction` 
* [ ] facebook gbdt feature `Practical Lessons from Predicting Clicks on Ads at Facebook.pdf`
* [ ] 综述 `Deep Learning based Recommender System- A Survey and New Perspectives.pdf`
* [ ] AutoRec `AutoRec- Autoencoders Meet Collaborative Filtering.pdf` 
* [ ] Deep Crossing `Deep Crossing- Web-Scale Modeling without Manually Crafted Combinatorial Features.pdf`
* [ ] Neural CF `Neural Collaborative Filtering.pdf`
* [ ] PNN `Product-based Neural Networks for User Response Prediction.pdf` 
* [ ] Wide & Deep `Wide & Deep Learning for Recommender Systems.pdf`
* [ ] FNN  `Deep Learning over Multi-field Categorical Data - A Case Study on User Response Prediction`
* [ ] DeepFM `DeepFM_A_Factorization-Machine_based_Neural_Networ.pdf`
* [ ] NFM `Neural Factorization Machines for Sparse Predictive Analytics.pdf`
* [ ] AFM  `Attentional Factorization Machines Learning the Weight of Feature Interactions via Attention Networks.pdf`
* [ ] DIN `Deep Interest Network for Click-Through Rate Prediction.pdf`
* [ ] DIEN `Deep Interest Evolution Network for Click-Through Rate Prediction.pdf`   [github-link](https://github.com/mouna99/dien)
* [ ] DRN `DRN: A Deep Reinforcement Learning Framework for News Recommendation`
* [ ] ESSM `Entire Space Multi-Task Model: An Effective Approach for Estimating Post-Click Conversion Rate`
* [ ] 在线离线评估 `Predictive Model Performance- Offline and Online Evaluations.pdf`
* [ ] MMR `The_Use_MMR_Diversity_Based_LTMIR_1998.pdf`
* [ ] DSSM `Learning Deep Structured Semantic Models for Web Search using Clickthrough Data`
* [ ] `airwise Multi-Layer Nets for Learning Distributed Representation of Multi-field Categorical Data`


## about git lfs

### LFS install
#### Linux
curl -s https://packagecloud.io/install/repositories/github/git-lfs/script.deb.sh | sudo bashs
sudo apt-get install git-lfs
git lfs install

#### Mac
- 安装HomeBrew /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
- brew install git-lfs
- git lfs install


### LFS usage
2. 执行 git lfs install 开启lfs功能
3. 使用 git lfs track 命令进行大文件追踪 例如git lfs track "*.png" 追踪所有后缀为png的文件
4. 使用 git lfs track 查看现有的文件追踪模式
5. 提交代码需要将gitattributes文件提交至仓库. 它保存了文件的追踪记录
6. 提交后运行git lfs ls-files 可以显示当前跟踪的文件列表
7. 将代码 push 到远程仓库后，LFS 跟踪的文件会以『Git LFS』的形式显示:
8. clone 时 使用'git clone' 或 git lfs clone均可

作者：amosbake
链接：https://www.jianshu.com/p/493b81544f80
来源：简书
