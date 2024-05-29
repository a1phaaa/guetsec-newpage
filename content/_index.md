---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        GUETSEC
      image:
        filename: logo.png
      text: |
        <br>
        
        桂林电子科技大学信息安全协会（GUETSEC）成立于2013年，由一批网络安全爱好者组成。这里有着自由的制度和开放、狂热的安全研究氛围。从这里走出的同学遍布阿里、腾讯、华为、360、奇安信等公司。社团的研究方向包括但不限于渗透测试，WEB安全，代码审计，二进制安全（逆向工程、系统安全），IOT安全，安全开发，密码学。

        我们多次代表学校参加网络安全竞赛（CTF夺旗赛）以及省级和国家级网络攻防演练，并多次在全国大学生信息安全竞赛、强网杯网络安全挑战赛、第五空间网络安全大赛等赛事中斩获佳绩。同时我们也与其他社团联合开展校赛，为我校网络安全人才培养贡献力量。

        在这里你可以尽情的展示你的才能，发挥你的奇思妙想。我们不能保证能给予你什么，但是你在这里的付出一定不会被辜负。

        Join us. To be what you want to be.

        期待一个有梦想的你。
  
  - block: collection
    content:
      title: 最新动态
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: event
    design:
      view: card
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
