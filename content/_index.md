---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing
cms_exclude: true

design:
  # Default section spacing
  spacing: "3rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/CVRoemer.pdf
    design:
      css_class: dark
      background: 
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: background.jpg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    id: paper
    content:
      title: 'Research'
      text: |
            #### Working papers
            - Effects of written self-promotions on gender bias and decision quality (with [Marina Schröder](https://www.inec.uni-hannover.de/de/schroeder))[[pdf]](/uploads/SelfPromotion_RoemerSchroederNov2024.pdf){{< spoiler text="Abstract" >}}Written self-promotion is crucial in numerous decision-making scenarios, including job applications,
            securing funds for start-ups, or academic grant proposals. In two experiments, we study the effects
            of self-promotions written by applicants on decision-makers, focusing on decision quality and gender bias. 
            show that providing such self-promotions slightly improves decision quality. Concerning gender bias, we
            find that self-promotions do not induce a gender bias that harms women. Moreover, the provision of selfpromotions
            can even eliminate pre-existing gender bias when no other performance signals are available.{{< /spoiler >}}
            - Piece-rate incentives and idea generation - An experimental analysis (with Katharina Laske and [Marina Schröder](https://www.inec.uni-hannover.de/de/schroeder)) 
            [Link to the word illustration task (WIT)](/wit/)[[pdf]](/uploads/IncentivesForIdeas_LaskeRoemerSchroeder.pdf){{< spoiler text="Abstract" >}}Understanding how organizational design affects idea generation is key to fostering innovation.
            In the context of idea generation, incentives may impact how hard ideators work (effort) and the types
            of ideas generated. We introduce two versions of a novel experimental task to quantify both of these
            effects. We show that piece-rate (PR) incentives increase the number of innovative ideas generated.
            Incentives lead to an increase in effort provision and a shift toward generating ideas that require less
            time in the realization. If anything, aligning incentives more closely to the desirable outcomes mitigates
            the effect of PR incentives on idea generation.{{< /spoiler >}}
            - A single voice is not enough: Evidence on female representation on expert panels in startup pitching contests (with [Richard Bläse](https://www.zhaw.ch/de/ueber-uns/person/blah/)){{< spoiler text="Abstract" >}}This study explores the dynamics of gender bias in expert panels using data from university-based
            startup-pitching contexts. Experts on these panels are primarily professional investors and assess
            a series of startups to determine contest winners. Our results indicate evidence for peer effects among
            such panels. First, we find that in-group bias with respect to gender in evaluations depends on the
            share of in-group experts on the panel. Second, observing dynamics in evaluations, we can show that
            evaluations change, once experts are exposed to the opinions of their fellow panelists. We document
            gender differences in both effects, highlighting the relevance of the design of such evaluation processes
            for gender biases.{{< /spoiler >}}

            #### Work in progress
            - It’s a match! Team composition and performance in innovation-related tasks (with [Joshua Graff-Zivin](https://www.joshgraffzivin.com/about)){{< spoiler text="Abstract" >}}We provide causal evidence of the effect of social connections on team formation preferences
            and team performance in an innovation-related task. Using a novel experimental design, we induce social
            connection in a large-scale online study via a short 2 minute video conversation. We can show that
            workers prefer to form a team with a lower-skilled worker they have communicated with prior to the team
            task than with higher-skilled workers they have not spoken to. This affects skill composition and social
            closeness within teams formed based on workers’ preferences. By examining team performance, we
            show that while social interaction can improve performance, preference-based matching offsets better
            outcomes. Our findings imply that self-formed teams may be configured sub-optimally as they can be
            biased by social connections.{{< /spoiler >}}
            - Group decisions (with [Alex Chan](https://www.alexchan.net/) and [Melisa Kurtis](https://ockenfels.uni-koeln.de/de/profil/melisa-kurtis)){{< spoiler text="Abstract" >}}Group decision-making is crucial in economic decisions, such as in corporate boards, research
            consortia, and hiring committees. We experimentally investigate the effects of diversity in priors and input
            aggregation mechanism on team performance in an estimation task. Groups in our experiment share
            the common objective to accurately estimate the ”type” of an imperfectly observed candidate. First, we
            exogenously vary group member priors and group (prior) diversity. We find that fully diverse groups
            make more accurate estimations than partially diverse or homogenous groups. Second, we vary the format
            of decision-making. The findings reveal that performance and benefits of diversity both depend on
            the group decision-making format. Group deliberation via online chat reduces accuracy. Initial speakers
            bias the group’s estimation towards their own priors, but first speakers with minority views (of priors) lead
            to more accurate group estimations.{{< /spoiler >}}
            - The effect of advice on self-evaluation(with [Marina Schröder](https://www.inec.uni-hannover.de/de/schroeder)){{< spoiler text="Abstract" >}}We experimentally examine how different advice formats affect self-evaluations. We find
            that advice given based on noisy performance signals increases self-evaluations and success of highperformers
            while reducing success for low-performers. Both genders respond similarly to proactive advice,
            given before self-evaluation. However, reactive advice—given after a preliminary self-evaluation—
            has stronger effects on women. Consequently, high-performing women benefit from advice more than
            men, whereas low-performing women are disadvantaged. Effects differ due to asymmetric reactions to
            advice by men. Thus, while reactive advice promotes high-performing women when performance signals
            are accurate, it disproportionately harms them when misclassified.{{< /spoiler >}}
            - The effect of affirmative action on self-promotion (with [Marina Schröder](https://www.inec.uni-hannover.de/de/schroeder)){{< spoiler text="Abstract" >}}Prior literature has shown that affirmative action can affect effort choices, investments tournament
            entries or unethical behavior towards peers. In an experimental study, we seek to investigate
            effects of affirmative action on self-promotion. We systematically vary the disadvantage potentially affirmed
            individuals are facing, and whether affirmative action is in place or not. Aiming to understand
            whether affirmative action may lead to underinvestment in support, I assess impacts on willingness to
            pay for AI assistance in revising self-promotions. With these results, I aim to shed light on potential side
            effects of affirmative action for affirmed individuals and to current debates on the effectiveness of such
            policies.{{< /spoiler >}}
  - block: markdown
    id: wit
    content:
      title: 'Word illustration task (WIT)'
      text: |
            {{< video src="video.mp4">}}
            
            WIT is an ideation task that comes with an objective performance measure and other great advantages (check out Laske, Römer and Schröder (2024) for details). Want to use WIT? Check out the easy-to-implement version I share on [Github](https://github.com/nathalieroemer/WIT.git).
            
            My personal top three ideas generated in experiments using this task
            
            1. 'Dragon' 
            ![Dragon reader text](dragon.png)
            
            2. 'Drums'
            ![Drums reader text](drums.png)
            
            3. 'Parrot'
            ![Parrot reader text](parrot.png)
  - block: markdown
    id: talks
    content:
      title: 'Prior & upcoming talks'
      text: |
            #### 2024
            GfeW (Cologne)
            #### 2023
            COPE (Amsterdam), Maastricht University Center of Neuroeconomics, EEA
            (Barcelona), Verein für Socialpolitik (Regensburg), RISE Workshop (Munich)
            #### 2022
            LESSAC Seminar (Dijon), ASFEE (Lyon), Brown Bag Seminar of the Organizational
            Economics Chair at LMU (Munich), ESA Europe (Bologna), Conference on
            Field Experiments in Strategy (London), 2nd Berlin Workshop on Empirical Public
            Economics: Gender Economics (Berlin)
            #### 2021
            ESA Global Online Around-the-Clock Meeting, GfeW (Magdeburg)
  - block: markdown
    id: ref
    content:
      title: 'References'
      text: | 
            <div style="text-align: center; margin-bottom: 2rem;">
            <strong>Marina Schröder</strong><br>
            Institute for Innovation Economics<br>
            Leibniz University Hannover<br>
            <a href="mailto:schroeder@inec.uni-hannover.de">schroeder@inec.uni-hannover.de</a>
            </div>

            <div style="display: grid; text-align: center; grid-template-columns: 1fr 1fr; gap: 2rem;">
            <div>
            <strong>Alex Chan</strong><br>
            Harvard Business School<br>
            Harvard University<br>
            <a href="mailto:achan@hbs.edu">achan@hbs.edu</a>
            </div>
            
            <div>
            <strong>Joshua Graff Zivin</strong><br>
            UC San Diego School of Global Policy and Strategy<br>
            <a href="mailto:jgraffzivin@ucsd.edu">jgraffzivin@ucsd.edu</a>
            </div>
            </div>

#    design:
#      view: list
#      columns: 1
#    filters:
#      folders:
#        - publication

## Did you find this page helpful? Consider sharing it 🙌
#    design:
#      view: list
#      columns: '1'
#  - block: markdown
#    id: papers
#    content:
#      title: Featured Publications
#      filters:
#        folders:
#          - publication
#        featured_only: false
#    design:
#      view: list
#      columns: 1
 # - block: collection
 #   content:
 #     title: Recent Publications
 #     text: ""
 #     filters:
 #       folders:
 #         - publication
 #       exclude_featured: false
 #   design:
 #     view: citation
#  - block: markdown
#    id: talks
#    content:
#      title: Prior & Upcoming Talks
#      filters:
#        folders:
#          - event
#    design:
#      view: list
#      columns: 1
#  - block: collection
#    id: news
#    content:
#      title: Recent News
#      subtitle: ''
#      text: ''
      # Page type to display. E.g. post, talk, publication...
#      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
#      count: 5
      # Filter on criteria
#      filters:
#        author: ""
#        category: ""
#        tag: ""
#        exclude_featured: false
#        exclude_future: false
#        exclude_past: false
#        publication_type: ""
      # Choose how many pages you would like to offset by
#      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
#      order: desc
#    design:
      # Choose a layout view
#      view: date-title-summary
      # Reduce spacing
#      spacing:
#        padding: [0, 0, 0, 0]
#  - block: cta-card
#    demo: true # Only display this section in the Hugo Blox Builder demo site
#    content:
#      title: 👉 Build your own academic website like this
#      text: |-
#        This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

 #       <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

#        Easily build anything with blocks - no-code required!
        
#        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
#      button:
#        text: Get Started
#        url: https://hugoblox.com/templates/
#    design:
#      card:
        # Card background color (CSS class)
#        css_class: "bg-primary-700"
#        css_style: ""
---