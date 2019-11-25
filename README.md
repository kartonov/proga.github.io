# proga.github.io
baseURL = "https://www.example.org/"
languageCode = "en-us"
theme = "aafu"

[params]
    title = "Aafu theme"
    author = "Darshan Baral"
    description = "Website title"
    copyright = "aaa"

    [params.theme]
        allowToggle = true
        # Available themes are 'light', 'dark', and 'pinkish'
        mainTheme = "light"
        altTheme = "dark"
        # setting false below will hide 'aafu by darshan' displayed under the profile pic
        showAttribute = true

    [params.favicons]
        use = true
        metas = '''
        <link rel="apple-touch-icon" sizes="180x180" href="apple-touch-icon.png">
        <link rel="icon" type="image/png" sizes="32x32" href="favicon-32x32.png">
        <link rel="icon" type="image/png" sizes="16x16" href="favicon-16x16.png">
        <link rel="manifest" href="site.webmanifest">
        <link rel="mask-icon" href="safari-pinned-tab.svg" color="#252627">
        <link rel="shortcut icon" href="favicon.ico">
        '''

    # Profile section
    [params.profile]
        name = "Киримова Анна"
		tagline = "Портфолио"
		location = "г. Абакан"
        photo = "1525505176537.jpg"

    # Section for links to social websites
    [params.social]
        title = "Links"

        [[params.social.list]]
            class = "fab"
            icon = "fa-linkedin-in"
            url = "#"
            title = "LinkedIn"		
        [[params.social.list]]
            class = "fab"
            icon = "fa-stack-overflow"
            url = "#"
            title = "StackOverflow"
        [[params.social.list]]
            class = "fab"
            icon = "fa-github"
            url = "#"
            title = "GitHub"
        [[params.social.list]]
            class = "fab"
            icon = "fa-twitter"
            url = "#"
            title = "Twitter"
		[[params.social.list]]
            class = "ai"
            icon = "ai-google-scholar"
            url = "#"
            title = "Google Scholar"
		[[params.social.list]]
            class = "ai"
            icon = "ai-researchgate"
            url = "#"
            title = "ResearchGate"

    #Specify what is showin in the Accordion
    [[params.showInAccordion]]
        item = "aboutme"
        expand = true   # true for the section that is initially expanded
    [[params.showInAccordion]]

        item = "education"
    [[params.showInAccordion]]

        item = "skill"
    [[params.showInAccordion]]
        item = "hobby"

    [params.aboutme]
        title = "Обо мне"
        icon = "fas fa-user"
        description = "**Ля=ля=ля**, а я сошла с ума какая досада ."

    # Education section
    [params.education]
        title = "Образование"
        icon = "fas fa-graduation-cap"

        [[params.education.list]]
            degree = "Не оконченное высшее образование"
            college = "Хакасский государственный университет им. Н.Ф. Катанова"
            dates = "2018 - 2022"
            thesis_title = "Влияние человека на других людей: исследование поведения человека."
            thesis_link = "#"
        [[params.education.list]]
            degree = "Среднее общее образование"
            college = "Ильичевская средняя школа"
            dates = "2007-2018"
            thesis_title = "Effect of humans on other humans: a study of human behavior."
            thesis_link = "#"
        [[params.education.list]]
            degree = "ла"
            college = "Детский садик"
            dates = "... - 2007"
            
          

   # Skill section
    [params.skill]
        title = "Общая характеристика"
        panelId = "skill-panel"
        icon = "fas fa-cogs"

        [[params.skill.list]]
            skill = "доброта и отзывчивость"
            skillrating = 90
        [[params.skill.list]]
            skill = "Сострадание к ближним"
            skillrating = 80
        [[params.skill.list]]
            skill = "Умение стебать друзей"
            skillrating = 99.9

    # Hobby section
    [params.hobby]
        title = "Увлечения"
        icon = "fas fa-gamepad"
		
        [[params.hobby.list]]		
		    hobby = "Готовка"
        [[params.hobby.list]]		
		    hobby = "Спортивные игры"
		    [[params.hobby.list]]		
		    hobby = "Компьютерные игры"
		    [[params.hobby.list]]		
		    hobby = "Просмотр сериалов"
