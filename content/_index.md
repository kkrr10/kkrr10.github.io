---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      button:
        text: CV
        url: uploads/CV_ryosuke_korekata_20241007.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: robot.png
          filters:
            brightness: 0.35
          size: cover
          position: center
          parallax: false
  # TODO:
  # - block: collection
  #   id: news
  #   content:
  #     title: Recent News
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: post
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: date-title-summary
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]
  # TODO:
  # - block: collection
  #   id: papers
  #   content:
  #     title: Featured Research
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     view: article-grid
  #     columns: 2
  - block: markdown
    id: publications
    content:
      title: '📜 Publications'
      subtitle: ''
      text: |
        ### Journal
        1. <div style="font-size: 0.8em">K. Kaneda, S. Nagashima, <u><strong>R. Korekata</strong></u>, M. Kambara, K. Sugiura, "Learning-To-Rank Approach for Identifying Everyday Objects Using a Physical-World Search Engine," <strong>IEEE RA-L</strong>, Vol. 9, No. 3, pp. 2088-2095, 2024, <a href="https://ieeexplore.ieee.org/abstract/document/10387680">pdf</a>, <a href="https://github.com/keio-smilab23/MultiRankIt">code</a>, <a href="https://youtu.be/eBBLGP9g6Zo">video</a>, <a href="https://speakerdeck.com/keio_smilab/iros24-learning-to-rank-approach-for-identifying-everyday-objects-using-a-physical-world-search-engine">slide</a>. DOI: 10.1109/LRA.2024.3352363 (<strong>IF: 5.2</strong>)</div>

        ### International Conference
        1. <div style="font-size: 0.8em">K. Kaneda, S. Nagashima, <u><strong>○R. Korekata</strong></u>, M. Kambara, K. Sugiura, "Learning-To-Rank Approach for Identifying Everyday Objects Using a Physical-World Search Engine," IEEE RA-L presented at <strong>IEEE/RSJ IROS</strong>, Abu Dhabi, Oct. 2024, <a href="https://ieeexplore.ieee.org/abstract/document/10387680">pdf</a>, <a href="https://github.com/keio-smilab23/MultiRankIt">code</a>, <a href="https://youtu.be/eBBLGP9g6Zo">video</a>, <a href="https://speakerdeck.com/keio_smilab/iros24-learning-to-rank-approach-for-identifying-everyday-objects-using-a-physical-world-search-engine">slide</a>.</div>
        1. <div style="font-size: 0.8em"><u><strong>○R. Korekata</strong></u>, K. Kanda, S. Nagashima, Y. Imai, K. Sugiura, "Multimodal Ranking for Target Objects and Receptacles Based on Open-Vocabulary Instructions," <strong>IEEE ICRA</strong> (Late Breaking Results), Yokohama, May 2024, <a href="uploads/korekata_icra24_multimodal/poster.pdf">poster</a>.</div>
        1. <div style="font-size: 0.8em"><u><strong>○R. Korekata</strong></u>, M. Kambara, Y. Yoshida, S. Ishikawa, Y. Kawasaki, M. Takahashi, K. Sugiura, "Switching Head–Tail Funnel UNITER for Dual Referring Expression Comprehension with Fetch-and-Carry Tasks," <strong>IEEE/RSJ IROS</strong>, pp. 3865-3872, Detroit, Oct. 2023, <a href="https://ieeexplore.ieee.org/abstract/document/10342165">pdf</a>, <a href="https://youtu.be/17hLj3Le0Kg">video</a>, <a href="https://speakerdeck.com/keio_smilab/iros23-switching-head-tail-funnel-uniter-for-dual-referring-expression-comprehension-with-fetch-and-carry-tasks">slide</a>, <a href="uploads/korekata_iros23_switching/poster.pdf">poster</a>. DOI: 10.1109/IROS55552.2023.10342165 (<strong>h5-index: 86</strong>)</div>
        1. <div style="font-size: 0.8em">K. Kaneda*, <u><strong>R. Korekata*</u></strong>, Y. Wada*, S. Nagashima*, ○M. Kambara, Y. Iioka, H. Matsuo, Y. Imai, T. Nishimura, K. Sugiura, "DialMAT: Dialogue-Enabled Transformer with Moment-Based Adversarial Training," <strong>IEEE/CVF CVPR</strong> (Embodied AI Workshop), Vancouver, Jun. 2023, <a href="https://embodied-ai.org/papers/2023/23.pdf">pdf</a>, <a href="https://github.com/keio-smilab23/DialMAT">code</a>, <a href="uploads/kaneda_cvprw23_dialmat/slide.pdf">slide</a>, <a href="uploads/kaneda_cvprw23_dialmat/poster.pdf">poster</a>. (<strong>*equal contribution</strong>, 🏆<a href="https://embodied-ai.org/cvpr2023/"><strong>1st Place in DialFRED Challenge</strong></a>)</div>
        1. <div style="font-size: 0.8em"><u><strong>○R. Korekata</u></strong>, Y. Yoshida, S. Ishikawa, K. Sugiura, "Switching Funnel UNITER: Multimodal Instruction Comprehension for Object Manipulation Tasks," <strong>IEEE/RSJ IROS</strong> (Late Breaking Results), Kyoto, Oct. 2022, <a href="uploads/korekata_iros22_switching/poster.pdf">poster</a>.</div>

        <a href="./slides/#international" style="color: #4B65E2;">See All Slides ></a>

        ### Under Review
        1. <div style="font-size: 0.8em"><u><strong>R. Korekata</strong></u>, K. Kaneda, S. Nagashima, Y. Imai, K. Sugiura, "DM<sup>2</sup>RM: Dual-Mode Multimodal Ranking for Target Objects and Receptacles Based on Open-Vocabulary Instructions," arXiv preprint arXiv:2408.07910, 2024, <a href="https://arxiv.org/pdf/2408.07910">pdf</a>, <a href="https://kkrr10.github.io/dm2rm/">project page</a>, <a href="https://kkrr10.github.io/dm2rm/#video">video</a>.</div>

        ### Domestic Conference (in Japanese🎌)
        1. <div style="font-size: 0.8em">○今井悠人, <u><strong>是方諒介</u></strong>, 杉浦孔明, "Dense Textを用いたマルチモーダルLLMに基づく大規模屋内環境における物体検索," 第42回日本ロボット学会学術講演会, 1L5-01, 大阪, 2024年9月, <a href="https://smilab.org/pdf/2024/2024-09-10T17:27:01+09:00_Yuto_Imai.pdf">pdf</a>, <a href="https://speakerdeck.com/keio_smilab/rsj24-object-retrieval-in-large-scale-indoor-environments-using-dense-text-with-a-multi-modal-large-language-model">slide</a>.</div>
        1. <div style="font-size: 0.8em">○八島大地, <u><strong>是方諒介</u></strong>, 杉浦孔明, "Multimodal LLMと二重緩和損失に基づく実世界検索エンジン," 第42回日本ロボット学会学術講演会, 3D2-07, 大阪, 2024年9月, <a href="https://smilab.org/pdf/2024/2024-09-10T17:31:50+09:00_Daichi_Yashima.pdf">pdf</a>, <a href="https://speakerdeck.com/keio_smilab/rsj24-open-vocabulary-mobile-manipulation-based-on-dual-relaxed-contrastive-learning-with-dense-labeling">slide</a>.</div>
        1. <div style="font-size: 0.8em"><u><strong>○是方諒介</u></strong>, 兼田寛大, 長嶋隼矢, 今井悠人, 杉浦孔明, "大規模言語モデルを用いたSwitching機構付きマルチモーダル検索モデルに基づく生活支援ロボットによる物体操作," 第38回人工知能学会全国大会, 3T5-OS-6b-04, 静岡, 2024年5月, <a href="https://www.jstage.jst.go.jp/article/pjsai/JSAI2024/0/JSAI2024_3T5OS6b04/_pdf">pdf</a>, <a href="https://speakerdeck.com/keio_smilab/jsai24-dm2rm-dual-mode-multimodal-ranking-for-target-objects-and-receptacles-based-on-open-vocabulary-instructions">slide</a>.</div>
        1. <div style="font-size: 0.8em">○今井悠人, 兼田寛大, <u><strong>是方諒介</u></strong>, 杉浦孔明, "マルチモーダル基盤モデルと緩和対照損失を用いた大規模屋内検索エンジン," 第38回人工知能学会全国大会, 3O5-OS-16c-04, 静岡, 2024年5月, <a href="https://www.jstage.jst.go.jp/article/pjsai/JSAI2024/0/JSAI2024_3O5OS16c04/_pdf">pdf</a>, <a href="https://speakerdeck.com/keio_smilab/jsai24-large-scale-indoor-search-engine-with-multimodal-foundation-models-and-relaxing-contrastive-loss">slide</a>.</div>
        1. <div style="font-size: 0.8em"><u><strong>○是方諒介</u></strong>, "大規模言語モデルを用いたマルチモーダル検索モデルに基づく生活支援ロボットによる物体操作," AICカンファレンス 2024, 神奈川, 2024年3月, <a href="uploads/korekata_aic24/poster.pdf">poster</a>.</div>
        1. <div style="font-size: 0.8em"><u><strong>○是方諒介</u></strong>, 和田唯我, 兼田寛大, 長嶋隼矢, 杉浦孔明, "DialMAT: 敵対的摂動に基づく対話的Vision-and-Language Navigation," 第41回日本ロボット学会学術講演会, 1K3-04, 宮城, 2023年9月, <a href="https://smilab.org/pdf/2023/2023-09-19T13:47:17+09:00_Ryosuke_Korekata.pdf">pdf</a>, <a href="https://github.com/keio-smilab23/DialMAT">code</a>, <a href="https://speakerdeck.com/keio_smilab/rsj23-dialmat-dialogue-enabled-transformer-with-moment-based-adversarial-training">slide</a>.</div>
        1. <div style="font-size: 0.8em">○兼田寛大, 長嶋隼矢, <u><strong>是方諒介</u></strong>, 杉浦孔明, "MultiRankIt: ランキング学習と大規模言語モデルによる物理世界検索," 第41回日本ロボット学会学術講演会, 2K1-01, 宮城, 2023年9月, <a href="https://smilab.org/pdf/2023/2023-09-19T13:46:45+09:00_Kanta_Kaneda.pdf">pdf</a>, <a href="https://speakerdeck.com/keio_smilab/rsj23-learning-to-rank-approach-for-identifying-everyday-objects-using-a-physical-world-search-engine">slide</a>.</div>
        1. <div style="font-size: 0.8em">○長嶋隼矢, <u><strong>是方諒介</u></strong>, 兼田寛大, 杉浦孔明, "マルチモーダル基盤モデルによる対象物体抽出に基づく日常物体検索および物体操作," 第41回日本ロボット学会学術講演会, 2J1-01, 宮城, 2023年9月, <a href="https://smilab.org/pdf/2023/2023-09-19T13:48:11+09:00_Shunya_Nagashima.pdf">pdf</a>, <a href="https://speakerdeck.com/keio_smilab/rsj23-everyday-object-search-and-manipulation-based-on-target-object-extraction-using-multimodal-foundation-models">slide</a>. (🏆<a href="https://x.com/keio_smilab/status/1701883420983378323"><strong>トヨタ自動車HSRコミュニティ優秀論文賞</strong></a>)</div>
        1. <div style="font-size: 0.8em"><u><strong>○是方諒介</u></strong>, 神原元就, 吉田悠, 石川慎太朗, 川崎陽祐, 髙橋正樹, 杉浦孔明, "Switching Head–Tail Funnel UNITERによる対象物体および配置目標に関する指示文理解と物体操作," 第37回人工知能学会全国大会, 2G4-OS-21d-01, 熊本, 2023年6月, <a href="https://www.jstage.jst.go.jp/article/pjsai/JSAI2023/0/JSAI2023_2G4OS21d01/_pdf">pdf</a>, <a href="https://speakerdeck.com/keio_smilab/jsai23-switching-head-tail-funnel-uniter-multimodal-instruction-comprehension-for-object-manipulation-tasks">slide</a>.</div>
        1. <div style="font-size: 0.8em"><u><strong>○是方諒介</u></strong>, "Switching Head–Tail Funnel UNITERによる対象物体および配置目標に関する指示文理解と物体操作," AICカンファレンス 2023, 神奈川, 2023年3月, <a href="https://koara.lib.keio.ac.jp/xoonips/modules/xoonips/detail.php?koara_id=KO11003001-20230304-0030">pdf</a>, <a href="uploads/korekata_aic23/poster.pdf">poster</a>.</div>
        1. <div style="font-size: 0.8em"><u><strong>○是方諒介</u></strong>, 吉田悠, 石川慎太朗, 杉浦孔明, "物体操作タスクにおけるSwitching Funnel UNITERによる対象物体および配置目標に関する指示文理解," 第40回日本ロボット学会学術講演会, 4F3-05, 東京, 2022年9月, <a href="https://smilab.org/pdf/2022/2022-10-11T16:16:03+09:00_Ryosuke_Korekata.pdf">pdf</a>, <a href="https://speakerdeck.com/keio_smilab/rsj22-switching-funnel-uniter-multimodal-instruction-comprehension-for-object-manipulation-tasks">slide</a>.</div>

        <a href="./slides/#domestic" style="color: #4B65E2;">See All Slides ></a>
    design:
      columns: '1'
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['80px', '0px', '20px', '0px']
  - block: resume-awards
    id: awards
    content:
      title: 🏆 Awards
      username: admin
    design:
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['80px', '0px', '20px', '0px']
  - block: markdown
    id: experience
    content:
      title: 'Experience'
      subtitle: ''
      text: |
        ### 🏢 Employments
        - <a href="https://global.toyota/en/mobility/frontier-research/">Toyota Motor Corporation Frontier Research Center</a>, Aichi.
          - Research Internship (Aug. 2023 - Sep. 2023)
        - <a href="https://www.keio.ac.jp/en/">Keio University</a>, Kanagawa.
          - Research Assistant (Apr. 2023 - Present)
        - <a href="https://www.sony.net/">Sony Corporation</a>, Tokyo.
          - Software Engineer Internship (Aug. 2021 - Sep. 2021)
        - <a href="https://aic.keio.ac.jp/en/">Keio University AI and Advanced Programming Consortium</a>, Kanagawa.
          - Education Internship (Oct. 2019 - Present)

        ### 🏫 Professional Memberships
        - <a href="https://www.rsj.or.jp/en/">The Robotics Society of Japan (RSJ)</a>
          - Student Member (Jul. 2024 - Present)
          - Student Editor (Jul. 2024 - Present)
        - <a href="https://www.ai-gakkai.or.jp/en/">The Japanese Society for Artificial Intelligence (JSAI)</a>
          - Student Member (Apr. 2023 - Present)

        ### 📘 Teaching
        - 慶應義塾大学理工学部情報工学科「機械学習基礎」
          - Teaching Assistant (Oct. 2024 - Mar. 2025)
        - "Machine Intelligence" at Keio University, Graduate School of Science and Technology
          - Teaching Assistant (Apr. 2024 - Sep. 2024)
        - 慶應義塾大学理工学部情報工学科「情報工学実験第2 - 知能ロボティクス実験」
          - Teaching Assistant (Oct. 2023 - Mar. 2024)
        - 横浜市立横浜サイエンスフロンティア高等学校「<a href="https://www.edu.city.yokohama.lg.jp/school/hs/sfh/index.cfm/32,0,77,html">サイエンスリテラシーⅠ</a>」
          - 講師 (Sep. 2022 - Sep. 2022)
          - Slides: <a href="https://speakerdeck.com/keio_smilab/ysfh-science-literacyi-text2image">Day1</a>, <a href="https://speakerdeck.com/keio_smilab/ysfh-science-literacyi-image2text">Day2</a>
    design:
      columns: '1'
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['80px', '0px', '20px', '0px']
  - block: markdown
    id: fellowships
    content:
      title: '🎓 Fellowships & Scholarships'
      subtitle: ''
      text: |
        ### Fellowships
        1. <div style="font-size: 0.8em"><a href="https://www.jsps.go.jp/english/e-pd/">JSPS Research Fellowship for Young Scientists (DC1)</a>, <strong>JPY 200K/month</strong>, Apr. 2025 - Mar. 2028.</div>
        1. <div style="font-size: 0.8em"><a href="https://www.jst.go.jp/program/boost/">JST Broadening Opportunities for Outstanding young researchers and doctoral students in STrategic areas (BOOST)</a>, <strong>JPY 300K/month</strong>, Oct. 2024 - Mar. 2025.</div>

        ### Scholarships
        1. <div style="font-size: 0.8em">Keio Graduate School Scholarship, <strong>JPY 500K</strong>, 2024 (Fall).</div>
        1. <div style="font-size: 0.8em">Repayment Exemption of <a href="https://www.jasso.go.jp/en/index.html">JASSO Scholarship (Category 1)</a>, <strong>JPY 1,584K</strong>, Apr. 2023 - Sep. 2024.</div>
        1. <div style="font-size: 0.8em">Keio Graduate School Scholarship, <strong>JPY 500K</strong>, 2024 (Spring).</div>
        1. <div style="font-size: 0.8em">Keio Graduate School Scholarship, <strong>JPY 500K</strong>, 2023.</div>
        1. <div style="font-size: 0.8em"><a href="https://www.dentsu-ikueikai.or.jp/scholarship/">DENTSU Scholarship Foundation for Graduate Students</a>, <strong>JPY 1,440K</strong>, Apr. 2023 - Sep. 2024.</div>
        1. <div style="font-size: 0.8em">Keio University Scholarship, <strong>JPY 250K</strong>, 2022.</div>
        1. <div style="font-size: 0.8em">Keio University Faculty of Science and Technology Alumni Association Scholarship, <strong>JPY 600K</strong>, 2022.</div>
        1. <div style="font-size: 0.8em">Keio University Scholarship, <strong>JPY 250K</strong>, 2021.</div>
        1. <div style="font-size: 0.8em">Keio University Faculty of Science and Technology Alumni Association Scholarship, <strong>JPY 600K</strong>, 2021.</div>
        1. <div style="font-size: 0.8em">Fudosan Mita-kai Scholarship, <strong>JPY 100K</strong>, 2020.</div>
        1. <div style="font-size: 0.8em">Keio University Scholarship, <strong>JPY 500K</strong>, 2020.</div>
        1. <div style="font-size: 0.8em">Keio University Iji-kai Scholarship, <strong>JPY 800K</strong>, 2019.</div>
        1. <div style="font-size: 0.8em"><a href="https://www.dentsu-ikueikai.or.jp/scholarship/">DENTSU Scholarship Foundation for Undergraduate Students</a>, <strong>JPY 3,360K</strong>, Apr. 2019 - Mar. 2023.</div>
    design:
      columns: '1'
      # background:
      #   color: 'gray'
      # TODO:
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['80px', '0px', '20px', '0px']
  - block: resume-skills
    id: skills
    content:
      title: 💻 Skills & Certifications
      username: admin
    design:
      show_skill_percentage: false
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['80px', '0px', '40px', '0px']
  - block: resume-languages
    content:
      title: 💬 Languages
      username: admin
    design:
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['10px', '0px', '20px', '0px']
  - block: markdown
    content:
      title: '📰 Misc'
      subtitle: ''
      text: |
        - 日刊工業新聞 (19面), 「<a href="https://www.nikkan.co.jp/articles/view/00724640">慶大、実世界検索エンジンで物探しの推薦効率向上</a>」, 2024年9月16日.
        - Research demonstration for the U.S. Ambassador to the United Nations and the State Minister for Foreign Affairs of Japan.
          - Keio University, "<a href="https://www.keio.ac.jp/en/news/2024/Apr/30/48-158580/">US Ambassador to the United Nations Linda Thomas-Greenfield Visits Keio University</a>," Apr. 30, 2024.
          - Ministry of Foreign Affairs of Japan, "<a href="https://www.mofa.go.jp/press/release/pressite_000001_00289.html">Participation of State Minister for Foreign Affairs TSUJI Kiyoto in Japan-U.S. Joint Event on Artificial Intelligence (AI)</a>," Apr. 18, 2024.
          - JIJI.com, 「<a href="https://www.jiji.com/jc/article?k=2024041801147&g=soc">ＡＩ研究の学生にエール　米国国連大使</a>」, 2024年4月18日. (ほか多数)
        - <a href="https://www.oreilly.co.jp/books/9784814400591/">ゼロから作るDeep Learning ❺ ―生成モデル編</a>, <a href="https://tree-radius-a8e.notion.site/80f8bfc333d244fdbd1f69a2acd37dc0">公開レビュー</a>, 2024年4月10日.
        - 「<a href="https://www.ymd.nii.ac.jp/tid-crest/event/jst-crest-imaiyamadasympo2024">JST CREST今井・山田チーム合同シンポジウム2024『信頼と文脈の研究がもたらす新たな人工知能』</a> 」, 2024年2月20日.
        - ロボ學, 「<a href="https://robogaku.jp/news/2023/rsj2022_4f3.html">学生編集委員企画：第40回日本ロボット学会学術講演会レポート（OS16：確率ロボティクスとデータ工学ロボティクス〜認識・行動学習・記号創発〜（4/4））</a>」, 2023年2月14日.
        - <a href="https://www.oreilly.co.jp/books/9784873119755/">ゼロから作るDeep Learning ❹ ―強化学習編</a>, <a href="https://tree-radius-a8e.notion.site/442ed77a97a64bd8aa5527fe66009817?v=dedb2b6f537c49278d07f6c8e7ebbbea">公開レビュー</a>, 2022年4月6日.
        - Journal Club (in Japanese🎌)
          1. <a href="https://speakerdeck.com/keio_smilab/journal-club-rrex-bot-remote-referring-expressions-with-a-bag-of-tricks">RREx-BoT [Sigurdsson+, IROS23]</a>
          1. <a href="https://speakerdeck.com/keio_smilab/journal-club-tidybot-personalized-robot-assistance-with-large-language-models">TidyBot [Wu+, IROS23]</a>
          1. <a href="https://speakerdeck.com/keio_smilab/journal-club-ifor-iterative-flow-minimization-for-robotic-object-rearrangement">IFOR [Goyal+, CVPR22]</a>
          1. <a href="https://speakerdeck.com/keio_smilab/journal-club-dialfred-dialogue-enabled-agents-for-embodied-instruction-following">DialFRED [Gao+, RA-L22]</a>
          1. <a href="https://speakerdeck.com/keio_smilab/journal-club-object-memory-transformer-for-object-goal-navigation">OMT [Fukushima+, ICRA22]</a>
          1. <a href="https://speakerdeck.com/keio_smilab/journal-club-following-natural-language-instructions-for-household-tasks-with-landmark-guided-search-and-reinforced-pose-adjustment">LGS-RPA [Murray+, RA-L22]</a>
          1. <a href="https://speakerdeck.com/keio_smilab/journal-club-a-simple-approach-for-visual-rearrangement-3d-mapping-and-semantic-search">Visual Rearrangement [Trabucco+, ICLR23]</a>
          1. <a href="https://speakerdeck.com/keio_smilab/journal-club-doorgym-a-scalable-door-opening-environment-and-baseline-agent">DoorGym [Urakami+, NeurIPSW19]</a>
          1. <a href="https://speakerdeck.com/keio_smilab/journal-club-mobile-former-bridging-mobilenet-and-transformer">Mobile-Former [Chen+, CVPR22]</a>
          1. <a href="https://speakerdeck.com/keio_smilab/journal-club-rapid-exploration-for-open-world-navigation-with-latent-goal-models">RECON [Shah+, CoRL21]</a>
          1. <a href="https://speakerdeck.com/keio_smilab/journal-club-iterative-shrinking-for-referring-expression-grounding-using-deep-reinforcement-learning">ISREG [Sun+, CVPR21]</a>
          1. <a href="https://speakerdeck.com/keio_smilab/journal-club-uniter-universal-image-text-representation-learning">UNITER [Chen+, ECCV20]</a>

          <a href="./slides/#journal-club" style="color: #4B65E2;">See All Slides ></a>
    # TODO: KTM?
    design:
      columns: '1'
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['80px', '0px', '40px', '0px']
---
