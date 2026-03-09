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
            - Effects of written self-promotions on gender bias and decision quality (with [Marina Schröder](https://www.inec.uni-hannover.de/de/schroeder))[[pdf]](/uploads/WP_Self-Promotion_Roemer_Schroeder.pdf)(under review){{< spoiler text="Abstract" >}}Written self-promotion is crucial in numerous decision-making scenarios, including job applications,
            securing funds for start-ups, or academic grant proposals. In two experiments, we study the effects
            of self-promotions written by applicants on decision-makers, focusing on decision quality and gender bias. 
            show that providing such self-promotions slightly improves decision quality. Concerning gender bias, we
            find that self-promotions do not induce a gender bias that harms women. Moreover, the provision of selfpromotions
            can even eliminate pre-existing gender bias when no other performance signals are available.{{< /spoiler >}}
            - Piece-rate incentives and idea generation - An experimental analysis (with Katharina Laske and [Marina Schröder](https://www.inec.uni-hannover.de/de/schroeder)) 
            [Link to the word illustration task (WIT)](/wit/)[[pdf]](https://www.cesifo.org/DocDL/cesifo1_wp11594.pdf){{< spoiler text="Abstract" >}}Understanding how organizational design affects idea generation is key to fostering innovation.
            In the context of idea generation, incentives may impact how hard ideators work (effort) and the types
            of ideas generated. We introduce two versions of a novel experimental task to quantify both of these
            effects. We show that piece-rate (PR) incentives increase the number of innovative ideas generated.
            Incentives lead to an increase in effort provision and a shift toward generating ideas that require less
            time in the realization. If anything, aligning incentives more closely to the desirable outcomes mitigates
            the effect of PR incentives on idea generation.{{< /spoiler >}}
            - Minority Judges, Major Impact? Conformity-Driven Gender Bias on Judging Panels for Startup Pitch Competitions (with [Richard Bläse](https://www.zhaw.ch/de/ueber-uns/person/blah/))[draft available upon request]{{< spoiler text="Abstract" >}}From funding pitches to job interviews, individuals often face panels—not single evaluators—whose decisions determine critical outcomes. Using novel data from Swiss startup pitch competitions, we show that the extent of in-group gender bias varies systematically with the panel’s gender composition. When the entrepreneur’s gender differs from the panel majority, same-gender judges exhibit a conformity-driven negative in-group bias, disadvantaging same-gender entrepreneurs. We establish a link between this bias and the judges’ relative confidence. Overall, our findings suggest that increasing female representation among judging panels—as often suggested—may not advance women’s success if they remain the panel minority.{{< /spoiler >}}
            - Guidance matters: Experimental evidence on effects of advice and feedback on self-evaluation (with [Marina Schröder](https://www.inec.uni-hannover.de/de/schroeder))[draft available upon request]{{< spoiler text="Abstract" >}}We experimentally investigate how guidance shapes workers’ self-evaluation. We observe that guidance from informed mentors increases the informativeness of self-evaluation independent of timing, aligning them more closely to actual performance. When offered prior to any self-assessment (advice) guidance equally increases (decreases) self-evaluation of workers who receive positive (negative) guidance. Guidance has asymmetric effects when provided based on an initial self-assessment (feedback), with stronger responses among of those receiving positive guidance. This particularly amplifying self-evaluation among workers’ classified as ‘high-potentials’, based on their performance. Although we find that initial self-evaluation influences mentors’ guidance, asymmetric effects are primarily driven by workers’ differential responses to guidance, rather than differences in its content. From the worker’s perspective, feedback is the most advantageous format of guidance while both advice and feedback enhance the efficiency of investment allocation by making self-evaluation more informative of actual performance.{{< /spoiler >}}
            - The effect of affirmative action on self-evaluation (with [Marina Schröder](https://www.inec.uni-hannover.de/de/schroeder))[draft available upon request]{{< spoiler text="Abstract" >}}We provide experimental evidence of the effects of inequality and affirmative action (AA) on self-evaluation and selection efficiency in competitive contests. The findings reveal that both inequality and AA significantly affect self-evaluation of those disadvantaged by it, while beneficiaries show no response. We document performance-dependent heterogeneity in responses to both inequality and AA, leading to reduced informativeness of self-evaluation. This tends to affect selection efficiency, increasing selection errors among decision-makers who select contest winners whenever inequality is in place. We observe that AA tends to additionally increase selection errors and that the increase is primarily due to the choice restrictions imposed.{{< /spoiler >}}

            #### Work in progress
            - It’s a match! Team composition and performance in innovation-related tasks (with [Joshua Graff-Zivin](https://www.joshgraffzivin.com/about))[draft in preparation]{{< spoiler text="Abstract" >}}We provide causal evidence of the effect of social connections on team formation preferences
            and team performance in an innovation-related task. Using a novel experimental design, we induce social
            connection in a large-scale online study via a short 2 minute video conversation. We can show that
            workers prefer to form a team with a lower-skilled worker they have communicated with prior to the team
            task than with higher-skilled workers they have not spoken to. This affects skill composition and social
            closeness within teams formed based on workers’ preferences. By examining team performance, we
            show that while social interaction can improve performance, preference-based matching offsets better
            outcomes. Our findings imply that self-formed teams may be configured sub-optimally as they can be
            biased by social connections.{{< /spoiler >}}
            - Deliberate? An Experiment on Team Decision Making (with [Alex Chan](https://www.alexchan.net/) and [Melisa Kurtis](https://ockenfels.uni-koeln.de/de/profil/melisa-kurtis))[draft in preparation]{{< spoiler text="Abstract" >}}Team decision-making is crucial in economic decisions, such as in corporate boards, research consortia, and hiring committees. We experimentally investigate the effects of diversity in priors and input
            aggregation mechanism on team performance in an estimation task. Teams in our experiment share
            the common objective to accurately estimate the ”type” of an imperfectly observed candidate. First, we
            exogenously vary team member priors and team (prior) diversity. We find that fully diverse teams
            make more accurate estimations than partially diverse or homogenous teams. Second, we vary the format
            of decision-making. The findings reveal that performance and benefits of diversity both depend on
            the team decision-making format. Team deliberation via online chat reduces accuracy. Initial speakers
            bias the team’s estimation towards their own priors, but first speakers with minority views (of priors) lead
            to more accurate team estimations.{{< /spoiler >}}
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
            #### 2026 (planned)
            SIOE (Fontainebleau), Verein für Socialpolitik (Innsbruck)
            #### 2025
            ESA Europe (Brno), Verein für Socialpolitik (Cologne)
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