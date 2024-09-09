---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a third year M.S. student at SIGS, Tsinghua University and I'm very fortune to be advised by Prof. Xueqian Wang. Before that, I received my bachelor’s degree in Electrical Engineering and Automation from Xi’an Jiaotong University in Jun. 2022. My currect research interest lies in RL and LLM, especially in alignment with AI feedback and AI safety. 

Currently, I'm an intern at Tencent AI Lab, AI for Science Center, supervised by Peilin Zhao.



Publications & Preprints
======

<table style="border-collapse: collapse; margin: 0; border: none;">
    <tr>
    <td style="border: none;"><img src="/images/WechatIMG476.png" alt="Probing the Safety Response Boundary of Large Language Models via Unsafe Decoding Path Generation" width="600"></td>
    <td style="border: none;"><a href="https://arxiv.org/abs/2408.10668"> Probing the Safety Response Boundary of Large Language Models via<br> Unsafe Decoding Path Generation</a>  <br><strong>Haoyu Wang</strong>, Bingzhe Wu, Yatao Bian, Yongzhe Chang, Xueqian Wang, Peilin Zhao<br> <span style="font-size: 0.8em;">Under review </span> </td>
  </tr>
    <tr>
    <td style="border: none;"><img src="/images/WechatIMG475.png" alt="Step-On-Feet Tuning: Scaling Self-Alignment of LLMs via Bootstrapping" width="600"></td>
    <td style="border: none;"> <a href="https://arxiv.org/abs/2402.07610"> Step-On-Feet Tuning: Scaling Self-Alignment of LLMs via Bootstrapping </a> <br>  <strong>Haoyu Wang</strong>, Guozheng Ma, Ziqiao Meng, Zeyu Qin, Li Shen, Zhong Zhang, Bingzhe Wu, Liu Liu, Yatao Bian, Tingyang Xu, Xueqian Wang, Peilin Zhao <br> <span style="font-size: 0.8em;">MHFAIA Workshop at ICML 2024 & Under review</span>   </td>
  </tr>
  <tr>
    <td style="border: none;"><img src="/images/WechatIMG474.png" alt="Are Large Language Models Really Robust to Word-Level Perturbations?" width="600"></td>
    <td style="border: none;"><a href="https://arxiv.org/abs/2309.11166"> Are Large Language Models Really Robust to Word-Level Perturbations?</a> <br> <strong>Haoyu Wang</strong>, Guozheng Ma, Cong Yu, Ning Gui, Linrui Zhang, Zhiqi Huang, Suwei Ma, Yongzhe Chang, Sen Zhang, Li Shen, Xueqian Wang, Peilin Zhao, Dacheng Tao <br> <span style="font-size: 0.8em;">SoLaR Workshop at NeurIPS 2023 & Under review</span></td>
  </tr>
  <tr>
    <td style="border: none;"><img src="/images/nips2023.png" alt="Learning better with less: effective augmentation for sample-efficient visual reinforcement learning" width="600"></td>
    <td style="border: none;"><a href="https://proceedings.neurips.cc/paper_files/paper/2023/hash/bc26087d3f82e62044fc77752e86737e-Abstract-Conference.html"> Learning better with less: effective augmentation for sample-efficient<br> visual reinforcement learning</a> <br>Guozheng Ma, Linrui Zhang, <strong>Haoyu Wang</strong>,  Lu Li, Zilin Wang, Zhen Wang, Li Shen, Xueqian Wang, Dacheng Tao <br><span style="font-size: 0.8em;">Advances in Neural Information Processing Systems 2023 </span> </td>
  </tr>
</table>

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
