
                    //"[+33]% Production when constructing [National Visitor's Center] wonders [in all cities]",
                    //"[+15]% Production when constructing [Hotel] buildings [in all cities]",
                    //"[-20]% Gold cost of upgrading <for [Military] units>",
                    /*"[+25]% Yield from every [Land Trade Route (Food)]",
                    //"[+1] population [in all cities]",
                    //"[+1 Happiness] [in all cities]",
[
	{
        "name": "Tradition",
        "era": "Ancient era",
        "uniques": [
            "[+3 Culture] from every [Palace]",
            "[-25]% Culture cost of natural border growth [in all cities]",
            "Comment [Unlocks [Hanging Gardens]]"
        ],
        "policies": [
            {
                "name": "Aristocracy",
                "uniques": [
                    "[+15]% Production when constructing [All] wonders [in all cities]",
                    "[+1 Happiness] per [10] population [in all cities]"
                ],
                "row": 1,
                "column": 1
            },
            {
                "name": "Legalism",
                "uniques": [
                    "Provides the cheapest [Culture] building in your first [4] cities for free",
                    "[+2 Culture] from every [National Epic]",
                    "[+2 Culture] from every [National College]",
                    "[+2 Culture] from every [Circus Maximus]",
                    "[+2 Culture] from every [Heroic Epic]",
                    "[+2 Culture] from every [East India Company]",
                    "[+2 Culture] from every [Grand Temple]",
                    "[+2 Culture] from every [Ironworks]",
                    "[+2 Culture] from every [Oxford University]",
                    "[+2 Culture] from every [Hermitage]",
                    "[+2 Culture] from every [National Intelligence Agency]"
                ],
                "row": 1,
                "column": 3
            },
            {
                "name": "Oligarchy",
                "uniques": [
                    "Units in cities cost no Maintenance",
                    "[+50]% Strength for cities <with a garrison> <when attacking>"
                ],
                "row": 1,
                "column": 5
            },
		{
                "name": "Nationalism",
                "uniques": [
                    "[+100]% XP gained from combat <for [All] units> <in [Friendly Land] tiles>"
                ],
		"requires": ["Aristocracy"],
                "row": 2,
                "column": 1
            },
            {
                "name": "Landed Elite",
                "uniques": [
                    "[+15]% growth [in capital]",
                    "[+2 Food] [in capital]"
                ],
                "requires": ["Legalism"],
                "row": 2,
                "column": 3
            },
            {
                "name": "Monarchy",
                "uniques": [
                    "[+1 Gold, +1 Happiness] per [2] population [in capital]"
                ],
                "requires": ["Legalism"],
                "row": 2,
                "column": 5
            },
            {
                "name": "Party Leadership",
                "uniques": [
                    "[+2 Food, +2 Gold, +1 Production, +1 Science] [in all cities]"
                ],
                "requires": ["Oligarchy","Socialist Realism"],
                "row": 2,
                "column": 7
            },
            {
                "name": "Socialist Realism",
                "uniques": [
                    "[+2 Happiness] from every [Monument]",
                    "[+100]% Production when constructing [Monument] buildings [in all cities]"
                ],
                "row": 1,
                "column": 7
            },
            {
                "name": "Tradition Complete",
                "uniques": [
                    "[+15]% growth [in all cities]",
                    "Provides a [Aqueduct] in your first [8] cities for free",
                    "May buy [Great Engineer] units for [1000] [Faith] [in all cities in which the majority religion is a major religion] at an increasing price ([500]) <starting from the [Industrial era]>"
                ]
            }
        ]
    },
    {
        "name": "Liberty",
        "era": "Classical era",
        "uniques": [
            "[+1 Culture] [in all cities]",
		 "Comment [Unlocks [The Pyramids]]"
        ],
        "policies": [
            {
                "name": "Citizenship",
                "uniques": [
                    "[-25]% construction time for [All] improvements",
                    "Free [Worker] appears"
                ],
                "row": 1,
                "column": 1
            },
		
		{
                "name": "Hero of the People",
                "uniques": [
                    "[+20]% Great Person generation [in all cities]"
                ],
                "row": 1,
                "column": 3
            },
		{
                "name": "Republic",
                "uniques": [
                    "[+1 Production] [in all cities]",
                    "[+5]% Production when constructing [All] buildings [in all cities]"
                ],
                "row": 1,
                "column": 5
            },
            {
                "name": "Collective Rule",
                "uniques": [
                    "[+50]% Production when constructing [Settler] units [in capital]",
                    "Free [Settler] appears"
                ],
                "requires": ["Republic"],
                "row": 2,
                "column": 1
            },
            {
                "name": "Representation",
                "uniques": [
                    "Each city founded increases culture cost of policies [33]% less than normal",
                    "Empire enters golden age"
                ],
                "requires": ["Citizenship"],
                "row": 2,
                "column": 3
            },
            {
                "name": "Meritocracy",
                "uniques": [
                    "[+15]% [Gold] [in all cities connected to capital]",
                    "[+1 Happiness] [in all cities connected to capital]",
                    "[-5]% Unhappiness from [Population] [in all non-occupied cities]"
                ],
                "requires": ["Citizenship"],
                "row": 2,
                "column": 5
            },{
                "name": "Volunteer Army",
                "uniques": [
                    "[3] free [Foreign Legion] units appear",
                    "[3] units cost no maintenance",
                    "[Gunpowder] units gain the [Morale] promotion",
                    "All newly-trained [Gunpowder] units [in all cities] receive the [Morale] promotion"
                ],
                "row": 1,
                "column": 7
            },
            {
                "name": "Civil Society",
                "uniques": [
                    "[-50]% Food consumption by specialists [in all cities]"
                ],
                "requires": ["Republic"],
                "row": 2,
                "column": 7
            },
            {
                "name": "Liberty Complete",
                "uniques": [
                    "Free Great Person",
                    "[+33]% Production when constructing [National Epic] wonders [in all cities]",
                    "[+33]% Production when constructing [National College] wonders [in all cities]",
                    "[+33]% Production when constructing [Circus Maximus] wonders [in all cities]",
                    "[+33]% Production when constructing [Heroic Epic] wonders [in all cities]",
                    "[+33]% Production when constructing [East India Company] wonders [in all cities]",
                    "[+33]% Production when constructing [Grand Temple] wonders [in all cities]",
                    "[+33]% Production when constructing [Ironworks] wonders [in all cities]",
                    "[+33]% Production when constructing [Oxford University] wonders [in all cities]",
                    "[+33]% Production when constructing [Hermitage] wonders [in all cities]",
                    "[+33]% Production when constructing [National Intelligence Agency] wonders [in all cities]",
                    //"[+33]% Production when constructing [National Visitor's Center] wonders [in all cities]",
                    
                    "[+15]% Production when constructing [Monument] buildings [in all cities]",
                    "[+15]% Production when constructing [Library] buildings [in all cities]",
                    "[+15]% Production when constructing [Colosseum] buildings [in all cities]",
                    "[+15]% Production when constructing [Barracks] buildings [in all cities]",
                    "[+15]% Production when constructing [Market] buildings [in all cities]",
                    "[+15]% Production when constructing [Temple] buildings [in all cities]",
                    "[+15]% Production when constructing [Workshop] buildings [in all cities]",
                    "[+15]% Production when constructing [University] buildings [in all cities]",
                    "[+15]% Production when constructing [Opera House] buildings [in all cities]",
                    "[+15]% Production when constructing [Constabulary] buildings [in all cities]",
                    //"[+15]% Production when constructing [Hotel] buildings [in all cities]",
                ]
            }
        ]
    },
    {
        "name": "Honor",
        "era": "Ancient era",
        "uniques": [
            "[+33]% Strength <vs [Barbarian] units>",
            "Earn [100]% of killed [Military] unit's [Strength] as [Culture]",
            "Comment [Unlocks [Statue of Zeus]]"
        ],
        "policies": [
            {
                "name": "Warrior Code",
                "uniques": [
                    "[2] free [Warrior] units appear",
                    "Earn [100]% of killed [Military] unit's [Strength] as [Gold]",
                    "[4] units cost no maintenance"
                ],
                "row": 1,
                "column": 1
            },
            {
                "name": "Military Tradition",
                "uniques": [
                    //"[-20]% Gold cost of upgrading <for [Military] units>",
                    "[+50]% Production when constructing [Courthouse] buildings [in all cities]",
                    "[+3 Production, +3 Gold, +3 Food] from every [Courthouse]",
                    "[+1 Food, +2 Science, +2 Culture] from every [Citadel]"
                ],
                "row": 1,
                "column": 3
            },
		{
                "name": "Discipline",
                "uniques": [
                    "[+100]% Production when constructing [Heroic Epic] wonders [in all cities]",
                    "[+4 Production, +4 Gold, +4 Culture, +4 Happiness] from every [Heroic Epic]",
                    "[50]% XP gained from combat <for [non-[Air]] units>"
                ],
                "row": 1,
                "column": 5
            },
            {
                "name": "Military Caste",
                "uniques": [
                    "Units in cities cost no Maintenance",
                    "[+1 Happiness, +2 Culture] [in all cities with a garrison]",
                    "[+2 Happiness] from every [Courthouse]"
                ],
                "requires": ["Warrior Code"],
                "row": 2,
                "column": 1
            },
            {
                "name": "Professional Army",
                "uniques": [
                    "[+1 Production, +1 Gold, +1 Culture] from every [Military Academy]",
                    "[+1 Production, +1 Gold, +1 Culture] from every [Armory]",
                    "[+1 Production, +1 Gold, +1 Culture] from every [Barracks]",
                    "[+100]% Production when constructing [Barracks] buildings [in all cities]",
                    "[+100]% Production when constructing [Armory] buildings [in all cities]",
                    "[+100]% Production when constructing [Military Academy] buildings [in all cities]"
                ],
                "requires": ["Military Tradition"],
                "row": 2,
                "column": 3
            },
		{
                "name": "Elite Forces",
                "uniques": [
                    "[+10]% Strength <for [Military] units>",
                    "[+10] HP when healing <for [Military] units>"
                ],
                "requires": ["Discipline"],
                "row": 2,
                "column": 5
            },
            {
                "name": "Militarism",
                "uniques": [
                    "[+1 Happiness] from every [Barracks]",
                    "[+1 Happiness] from every [Armory]",
                    "[+1 Happiness] from every [Military Academy]"
                ],
                "row": 1,
                "column": 7
            },
            {
		"name": "Fortified Borders",
		"uniques": [
				"[+1 Happiness] from every [Castle]","[+1 Happiness] from every [Arsenal]","[+1 Happiness] from every [Military Base]"
			],
                "requires": ["Militarism"],
		"row": 2,
		"column": 7
	},
            {
                "name": "Honor Complete",
                "uniques": [
                    "[+10]% [Food] [in all cities]",
                    "Earn [100]% of killed [Military] unit's [Strength] as [Science]",
                    "May buy [Great General] units for [1000] [Faith] [in all cities in which the majority religion is a major religion] at an increasing price ([500]) <starting from the [Industrial era]>"
                ]
            }
        ]
    },
    {
        "name": "Piety",
        "era": "Ancient era",
        "uniques": [
            "[+100]% Production when constructing [Temple] buildings [in all cities]",
            "[+100]% Production when constructing [Shrine] buildings [in all cities]",
		"Only available <before adopting [World]>",
            "[+1 Culture, +1 Faith] [in capital]",
            "Comment [Unlocks [Hagia Sophia]]"
        ],
        "policies": [
            {
                "name": "Mandate Of Heaven",
                "uniques": [
                    "[+1 Happiness] from every [Temple]",
                    "[+1 Faith] [in capital]",
                    "[Faith] cost of purchasing items in cities [-20]%"
                ],
                "row": 1,
                "column": 1
            },
            {
                "name": "Organized Religion",
                "uniques": [
                    "[+1 Culture, +1 Faith] from every [Shrine]",
                    "[+1 Culture, +1 Faith] from every [Temple]"
                ],
                "row": 1,
                "column": 3
            },
            {
                "name": "Theocracy",
                "uniques": [
                    "[+33]% [Gold] from every [Grand Temple]",
                    "[+1 Gold] from every [Temple]",
                    "[+1 Gold] from every [Shrine]",
                    "[+3 Gold] from every [Holy site]"
                ],
                "row": 1,
                "column": 5
            },
            {
                "name": "Reformation",
                "uniques": [
                    "[-15]% Culture cost of natural border growth [in all cities]",
                    "May choose [1] additional [Enhancer] beliefs when [founding] a religion",
                    "Gain a free [Enhancer] belief <after founding a religion>"
                ],
                "requires": [
                    "Organized Religion"
                ],
                "row": 2,
                "column": 1
            },
            {
                "name": "Religious Tolerance",
                "uniques": [
                    "[+1 Culture, +1 Faith] [in all cities]",
                    "[+25]% [Science] from every [Grand Temple]",
                    "[+2 Science] from every [Temple]"
                ],
                "requires": ["Organized Religion"],
                "row": 2,
                "column": 5
            },
		{
            "name": "Theology",
            "uniques": [
                "[-25]% construction time for [All] improvements",
                "Free [Worker] appears"
            ],
		"requires": ["Mandate Of Heaven","Theocracy"],
            "row": 2,
            "column": 3
        },
		{
				"name": "Promised Land",
				"uniques": [
					"[+100]% Strength for cities <with a garrison> <when defending>"
				],
                		"requires": ["Theology"],
				"row": 3,
				"column": 3
			},
            {
                "name": "Piety Complete",
                "uniques": [
                    "Free [Great Prophet] appears",
                    "[+1 Food, +3 Culture] from every [Holy site]",
                    "Provides a [Garden] in your first [4] cities for free",
                    "May buy [Piety Complete Building] buildings for [1875] [Faith] [in capital] <(modified by game speed)> <hidden from users> <starting from the [Industrial era]>",
                    "Comment [May buy [{non-[Great Scientist]} {Great Person}] units for [1875] [Faith] [in capital] [(modified by game speed)] [once] [starting from the [Industrial era]]]"
                ]
            }
        ]
    },
    {
        "name": "Patronage",
        "era": "Medieval era",
        "uniques": [
            "Resting point for Influence with City-States is increased by [20]",
            "Comment [Unlocks [Forbidden Palace]]"
        ],
        "policies": [
            {
                "name": "Consulates",
                "uniques": [
                    "Resting point for Influence with City-States is increased by [20]"
                ],
                "row": 1,
                "column": 1
            },
            {
                "name": "Merchant Confederacy",
                "uniques": [
                    "[+2 Production, +2 Food] from each Trade Route",
                    "[+2 Gold, +2 Culture] from each Trade Route"
                ],
                "row": 1,
                "column": 3
            },
		{
                		"name": "United Front",
                		"uniques": [
                    		"Militaristic City-States grant units [2] times as fast when you are at war with a common nation","[-100]% weight to this choice for AI decisions"
                			],
                			"row": 1,
                			"column": 5
            		},
            {
                "name": "Scholasticism",
                "uniques": [
                    "Allied City-States provide [Science] equal to [25]% of what they produce for themselves"
                ],
                "requires": ["Merchant Confederacy"],
                "row": 2,
                "column": 1
            },
            {
                "name": "Cultural Diplomacy",
                "uniques": [
                    "[+100]% resources gifted by City-States",
                    "[+50]% Happiness from luxury resources gifted by City-States"
                ],
                "requires": ["Merchant Confederacy"],
                "row": 2,
                "column": 3
            },
            {
                "name": "Philanthropy",
                "uniques": [
                    "Gifts of Gold to City-States generate [25]% more Influence",
                    "[-25]% City-State Influence degradation"
                ],
                "requires": ["Merchant Confederacy"],
                "row": 2,
                "column": 5
            },
		{
            "name": "Globalization",
            "uniques": [
                "[+20]% Great Person generation [in all cities]"
            ],
                "requires": ["Cultural Diplomacy"],
            "row": 3,
            "column": 3
        },
            {
                "name": "Patronage Complete",
                "uniques": [
                    "[+50]% [Culture] from City-States",
                    "[+50]% [Faith] from City-States",
                    "[+50]% [Food] from City-States",
                    "[+50]% [Happiness] from City-States",
                    "Allied City-States will occasionally gift Great People"
                ]
            }
        ]
    },
    {
        "name": "Commerce",
        "uniques": [
            "[Great Merchant] is earned [33]% faster",
            "Comment [Unlocks [Big Ben]]"
        ],
        "era": "Medieval era",
        "policies": [
            {
                "name": "Silk Road",
                "uniques": [
                    "[+50]% Production when constructing [Market] buildings [in all cities]",
                    "[+50]% Production when constructing [Bank] buildings [in all cities]",
                    "[+50]% Production when constructing [Stock Exchange] buildings [in all cities]"
                ],
                "row": 1,
                "column": 1
            },
		{
                "name": "Economic Union",
                "uniques": [
                    "[+25]% [Gold] [in all cities]",
                ],
                "row": 1,
                "column": 3
            },
		{
				"name": "Mercenary Army",
				"uniques": ["May buy [Landsknecht] units with [Gold] for [3] times their normal Production cost",
						"May buy [Foreign Legion] units with [Gold] for [5] times their normal Production cost"],
				"row": 1,
				"column": 5
			},
            {
                "name": "Entrepreneurship",
                "uniques": [
                    "[-25]% maintenance on road & railroads",
                    "[-25]% maintenance cost for buildings [in all cities]",
                    "Provides [2] [Porcelain]"
                ],
                "requires": ["Silk Road","Economic Union"],
                "row": 2,
                "column": 1
            },
            {
                "name": "Mercantilism",
                "uniques": [
                    /*"[+25]% Yield from every [Land Trade Route (Food)]",
                    "[+25]% Yield from every [Land Trade Route (Production)]",
                    "[+25]% Yield from every [Sea Trade Route (Food)]",
                    "[+25]% Yield from every [Sea Trade Route (Production)]",*/
                    "[Gold] cost of purchasing items in cities [-20]%",
                    "[+2 Science] from every [Market]",
                    "[+2 Science] from every [Bank]",
                    "[+2 Science] from every [Stock Exchange]"
                ],
                "requires": ["Silk Road"],
                "row": 2,
                "column": 3
            },
            {
                "name": "Protectionism",
                "uniques": [
                    "[+1 Food, +4 Gold] from every [Customs house]",
                    "[+4 Production, +4 Culture, +4 Happiness] from every [Market]"
                ],
                "requires": ["Economic Union","Silk Road"],
                "row": 2,
                "column": 5
            },
		{
            "name": "Distributed Sovereignty",
            "uniques": [
                "[+1 Production] [in all cities]",
                "[+5]% Production when constructing [All] buildings [in all cities]"
            ],
                "requires": ["Mercantilism"],
            "row": 3,
            "column": 3
        },
            {
                "name": "Commerce Complete",
                "uniques": [
                    "[2] free [Great Merchant] units appear",
                    "[+1 Food] from every [Trading post]",
                    "[+1 Food] from every [Market]",
                    "[+100]% Gold from Great Merchant trade missions",
                    "May buy [Great Merchant] units for [1000] [Faith] [in all cities in which the majority religion is a major religion] at an increasing price ([500]) <starting from the [Industrial era]>"
                ]
            }
        ]
    },
    {
        "name": "Exploration",
        "uniques": [
            "[+1] Movement <for [{Military} {Water}] units>",
            "[+1] Sight <for [{Military} {Water}] units>",
            "Comment [Unlocks [The Louvre]]",
            "Comment [Unlocks [Conquistador]]"
        ],
        "era": "Medieval era",
        "policies": [
            {
                "name": "Naval Tradition",
                "uniques": [
                    "[+1 Happiness, +1 Culture] from every [Lighthouse]",
                    "[+1 Happiness, +1 Culture] from every [Harbor]",
                    "[+1 Happiness, +1 Culture] from every [Seaport]"
                ],
                "row": 1,
                "column": 1
            },
            {
                "name": "Maritime Infrastructure",
                "uniques": [
                    "[+3 Production] [in all coastal cities]",
                    "[+50]% Production when constructing [Lighthouse] buildings [in all cities]",
                    "[+50]% Production when constructing [Harbor] buildings [in all cities]",
                    "[+50]% Production when constructing [Seaport] buildings [in all cities]"
                ],
                "row": 1,
                "column": 3
            },
            {
                "name": "Colonialism",
                "uniques": [
                    //"[+1] population [in all cities]",
                    //"[+1 Happiness] [in all cities]",
                    "Gain a free [Workshop] [in this city] <upon founding a city>",
                    "Free [Worker] appears <upon founding a city>"
                ],
                "row": 1,
                "column": 5
            },
            {
                "name": "Navigation School",
                "uniques": [
                    "[+2 Science] [in all coastal cities]",
                    "[+10]% Strength <for [Water] units>"
                ],
                "requires": ["Maritime Infrastructure","Naval Tradition"],
                "row": 2,
                "column": 3
            },
		{
                "name": "Resettlements",
                "uniques": [
                    "[+4] population [in this city] <upon founding a city>",
                    "Gain a free [Workshop] [in this city] <upon founding a city>",
                    "Gain a free [Monument] [in this city] <upon founding a city>",
                    "Gain a free [Granary] [in this city] <upon founding a city>",
                    "Gain a free [Library] [in this city] <upon founding a city>",
                    "Gain a free [Aqueduct] [in this city] <upon founding a city>"
                ],
		"requires": ["Colonialism"],
                "row": 2,
                "column": 5
            },
	{
            "name": "Conservation",
            "uniques": [
                "[+20]% Great Person generation [in all cities]"
            ],
		"requires": ["Naval Tradition"],
            "row": 3,
            "column": 1
        },
            {
                "name": "Treasure Fleets",
                "uniques": [
                    "[+1 Gold, +1 Production, +1 Food] from every [Coast] <in tiles without [resource]> <in tiles without [Improvement]>",
                    "[+1 Gold, +1 Production, +1 Food] from every [Ocean]"
                ],
                "requires": ["Navigation School","Resettlements"],
                "row": 3,
                "column": 3
            },
            {
                "name": "Exploration Complete",
                "uniques": [
                    "[Great General] is earned [100]% faster",
                    "Free [Great General] appears",
                    "[+1] Happiness from each type of luxury resource",
                    "May buy [Great Engineer] units for [1000] [Faith] [in all cities in which the majority religion is a major religion] at an increasing price ([500]) <starting from the [Industrial era]>"
                ]
            }
        ]
    },
	{
        "name": "Aesthetics",
        "era": "Classical era",
        "uniques": [
            "[Great Artist] is earned [25]% faster",
            "Comment [Unlocks [Uffizi]]"
        ],
        "policies": [
            {
                "name": "Free Mind",
                "uniques": [
                    "[Great Artist] is earned [33]% faster",
                    "[+20]% [Gold] <in cities with a [Theatre]>",
                    "[+20]% [Gold] <in cities with a [Museum]>",
                    "[+20]% [Gold] <in cities with a [Broadcast Tower]>"
                ],
                "row": 1,
                "column": 1
            },
		{
                "name": "Cultural Centers",
                "uniques": [
                    "[+100]% Production when constructing [Amphitheater] buildings [in all cities]",
                    "[+100]% Production when constructing [Opera House] buildings [in all cities]",
                    "[+100]% Production when constructing [Museum] buildings [in all cities]",
                    "[+100]% Production when constructing [Broadcast Tower] buildings [in all cities]",
                    "[+1 Happiness] from every [Amphitheater]",
                    "[+1 Happiness] from every [Opera House]",
                    "[+1 Happiness] from every [Theatre]"
                ],
                "row": 1,
                "column": 3
            },
            {
                "name": "Cultural Exchange",
                "uniques": [
                    "Free [Great Artist] appears",
                    "[+1 Culture] from every [Great Improvement]",
                    "[+1 Culture] from every [Trading post]",
                    "[+1 Culture] from every [Brazilwood Camp]",
                    "[+1 Culture] from every [Kasbah]",
                    "[+1 Culture] from every [Moai]",
                    "[+1 Culture] from every [Chateau]"
                ],
                "row": 1,
                "column": 5
            },
            {
                "name": "Artistic Genius",
                "uniques": [
                    "Free [Great Artist] appears",
                    "[+1 Science] from every [Museum]",
                    "[+1 Science] from every [Amphitheater]",
                    "[+1 Science] from every [Opera House]",
                    "[+1 Science] from every [Broadcast Tower]",
                    "[+3 Science] from every [Theatre]",
                    "[+2 Science] from every [Landmark]"
                ],
                "requires": ["Free Mind","Cultural Centers"],
                "row": 2,
                "column": 3
            },
		{
                "name": "Fine Arts",
                "uniques": [
                    "Gain a free [Theatre] [in all cities]"
                ],
                "requires": ["Artistic Genius","Cultural Exchange"],
                "row": 3,
                "column": 1
            },
            {
                "name": "Flourishing of the Arts",
                "uniques": [
                    "[+1 Culture] from every [Theatre]",
                    "[+1 Culture] from every [World Wonder]",
                    "Empire enters golden age"
                ],
                "requires": ["Artistic Genius","Cultural Exchange"],
                "row": 3,
                "column": 3
            },
            {
                "name": "Aesthetics Complete",
                "uniques": [
                    "[+100]% Production when constructing [Worker] units [in all cities]",
                    "[+1 Culture] from every [Theatre]",
                    //need implement "Shows Hidden Antiquity Sites"
                    "Free Social Policy",
                    "May buy [Great Artist] units for [1000] [Faith] [in all cities in which the majority religion is a major religion] at an increasing price ([500]) <starting from the [Industrial era]>"
                ]
            }
        ]
    },
    {
        "name": "Rationalism",
        "era": "Renaissance era",
        "uniques": [
            "[Great Scientist] is earned [20]% faster",
		"Only available <before adopting [World]>",
            "Comment [Unlocks [Porcelain Tower]]"
        ],
        "policies": [
		{
                "name": "Sovereignty",
                "uniques": [
                    "[+1 Gold] from every [Library]",
                    "[+1 Gold] from every [University]",
                    "[+1 Gold] from every [Observatory]",
                    "[+1 Gold] from every [Research Lab]",
                    "[+1 Gold] from every [Public School]"
                ],
                "row": 1,
                "column": 1
            },
            {
                "name": "Free Thought",
                "uniques": [
                    "[+1 Science] from every [Trading post]",
                    "[+1 Science] from every [Chateau]",
                    "[+1 Science] from every [Kasbah]",
                    "[+1 Science] from every [Brazilwood Camp]",
                    "[+4 Science] from every [Customs house]",
                    "[+4 Science] from every [Academy]"
                ],
                "row": 1,
                "column": 3
            },
            {
                "name": "Humanity",
                "uniques": [
                    "[+50]% Production when constructing [Library] buildings [in all cities]",
                    "[+50]% Production when constructing [University] buildings [in all cities]",
                    "[+50]% Production when constructing [Observatory] buildings [in all cities]",
                    "[+50]% Production when constructing [Public School] buildings [in all cities]",
                    "[+50]% Production when constructing [Research Lab] buildings [in all cities]"
                ],
                "row": 1,
                "column": 5
            },
        {
            "name": "Optimization Imperative",
            "uniques": [
                "Each city founded increases culture cost of policies [33]% less than normal",
                "Empire enters golden age"
            ],
            "requires": ["Sovereignty"],
            "row": 2,
            "column": 1
        },
            {
                "name": "Scientific Revolution",
                "uniques": [
                    "Free [Great Scientist] appears"
                ],
                "requires": ["Free Thought","Sovereignty"],
                "row": 2,
                "column": 3
            },
            {
                "name": "Secularity",
                "uniques": [
                    "[+2 Science] from every specialist [in all cities]"
                ],
		    "requires": ["Humanity"],
                "row": 2,
                "column": 5
            },
		{
				"name": "Christianity",
				"uniques": ["[+2 Production, +2 Food, +2 Gold, +2 Faith, +2 Culture, +2 Science, +2 Happiness] per [5] population [in all cities]",
					"[Faith] cost of purchasing [Missionary] units [-20]%","[2] free [Missionary] units appear"],
				"requires": ["Secularity"],
				"row": 3,
				"column": 3
			},

            {
                "name": "Rationalism Complete",
                "uniques": [
                    "[10]% [Science] <while the empire is happy>","[-10]% unhappiness from the number of cities"
                ]
            }
        ]
    },
  {
        "name": "World",
        "era": "Industrial era",
        "uniques": [
            "[-1 Culture] [in all cities]", "Only available <before adopting [Freedom]>",
		"Only available <before adopting [Piety]>", "Only available <before adopting [Rationalism]>"
        ],
        "policies": [
            {
                "name": "Populism",
                "uniques": [
                    "[+25]% construction time for [All] improvements",
                    "Free [Worker] appears"
                ],
                "row": 1,
                "column": 1
            },
  {
            "name": "Mysticism",
            "uniques": [
                "[-20]% Great Person generation [in all cities]"
            ],
            "row": 1,
            "column": 3
        },
        {
            "name": "Free Religion",
            "uniques": [
                "[-50]% Production when constructing [Mechanized Infantry] units [in capital]",
                "Free [Settler] appears"
            ],
            "requires": ["Mysticism"],
            "row": 2,
            "column": 1
        },
        {
            "name": "Dictatorship of the Proletariat",
            "uniques": [
                "Each city founded increases culture cost of policies [11]% less than normal",
                "Empire enters golden age"
            ],
            "requires": ["Populism","Mysticism"],
            "row": 2,
            "column": 3
        },
	{
            "name": "Planned Economy",
            "uniques": [
                "[-1 Production] [in all cities]",
                "[-5]% Production when constructing [All] buildings [in all cities]"
            ],
            "requires": ["Mysticism"],
            "row": 2,
            "column": 5
        },
        {
            "name": "Scorched Earth",
            "uniques": [
                "[-15]% [Gold] [in all cities connected to capital]",
                "[-1 Happiness] [in all cities connected to capital]",
                "[+5]% Unhappiness from [Population] [in all non-occupied cities]"
            ],
            "requires": ["Dictatorship of the Proletariat"],
            "row": 3,
            "column": 3
        },
        {
            "name": "World Complete",
            "uniques": [
                "Free Great Person"
            ]
        }
    ]
},
{
    "name": "Recorded History",
    "era": "Classical era",
    "uniques": [
        "[+1 Culture] [in all cities]", "Free Social Policy", "Comment [Unlocks [The Great Library]]"
    ],
    "policies": [
        {
            "name": "Games and Recreation",
            "uniques": [
                "[-25]% construction time for [All] improvements",
                "Free [Worker] appears"
            ],
            "row": 1,
            "column": 1
        },
	{
            "name": "Medieval Faires",
            "uniques": [
                "[+1 Production] [in all cities]",
                "[+5]% Production when constructing [All] buildings [in all cities]"
            ],
            "row": 1,
            "column": 3
        },
        {
            "name": "Natural History",
            "uniques": [
                "[+50]% Production when constructing [Scout] units [in capital]",
                "Free [Settler] appears"
            ],
            "row": 1,
            "column": 5
        },
	{
            "name": "Opera and Ballet",
            "uniques": [
                "[+20]% Great Person generation [in all cities]"
            ],
            "requires": ["Games and Recreation"],
            "row": 2,
            "column": 1
        },
        {
            "name": "Professional Sports",
            "uniques": [
                "[+15]% [Gold] [in all cities connected to capital]",
                "[+1 Happiness] [in all cities connected to capital]",
                "[-5]% Unhappiness from [Population] [in all non-occupied cities]"
            ],
            "requires": ["Opera and Ballet"],
            "row": 3,
            "column": 1
        },
        {
            "name": "Mass Media",
            "uniques": [
                "Each city founded increases culture cost of policies [33]% less than normal",
                "Empire enters golden age"
            ],
            "requires": ["Medieval Faires","Natural History","Opera and Ballet"],
            "row": 3,
            "column": 3
        },
        {
            "name": "Recorded History Complete",
            "uniques": [
                "Free Great Person"
            ]
        }
    ]
},
    {
        "name": "Order",
        "era": "Industrial era",
        "uniques": [
            "Free Social Policy",
            "Comment [Unlocks [Kremlin]]",
            "Only available <before adopting [Autocracy]>",
            "Only available <before adopting [Freedom]>"
        ],
        "policies": [
            {
                "name": "Double Agents",
                "uniques": [
                    "[-100]% enemy spy effectiveness [in all cities connected to capital]",
                    //Unique for increasing chance of killing spy
                ],
                "row": 1,
                "column": 7
            },
            {
                "name": "Young Pioneers",
                "uniques": [
                    "[+1 Happiness] from every [Workshop]",
                    "[+1 Happiness] from every [Factory]",
                    "[+1 Happiness] from every [Solar Plant]",
                    "[+1 Happiness] from every [Nuclear Plant]",
                    "[+1 Happiness] from every [Hydro Plant]"
                ],
                "row": 1,
                "column": 1
            },
            {
                "name": "Skyscrapers",
                "uniques": [
                    "[Gold] cost of purchasing [All] buildings [-50]%"
                ],
            		"requires": ["Young Pioneers","Workers' Faculties"],
                "row": 2,
                "column": 1
            },
            {
                "name": "Academy of Sciences",
                "uniques": [
                    "[+1 Happiness] from every [Observatory]",
                    "[+1 Happiness] from every [Public School]",
                    "[+1 Happiness] from every [Research Lab]"
                ],
            		"requires": ["Young Pioneers","Workers' Faculties","People's Army"],
                "row": 2,
                "column": 3
            },
            {
                "name": "Cultural Revolution",
                "uniques": [
                    "[+10]% [Culture] [in all cities] <while the empire is happy>",
                    "Empire enters golden age"
                ],
            		"requires": ["Double Agents","Workers' Faculties","People's Army"],
                "row": 2,
                "column": 5
            },
            {
                "name": "Patriotic War",
                "uniques": [
                    "[+10]% Strength <for [Military] units> <when fighting in [Friendly Land] tiles>",
                    "[+50]% XP gained from combat <for [non-[Air]] units>"
                ],
            		"requires": ["Double Agents","People's Army"],
                "row": 2,
                "column": 7
            },
            {
                "name": "Workers' Faculties",
                "uniques": [
                    "[+25]% [Science] <in cities with a [Factory]>",
                    "[+100]% Production when constructing [Factory] buildings [in all cities]"
                ],
                "row": 1,
                "column": 3
            },
            {
                "name": "Five-Year Plan",
                "uniques": [
                    "[+2 Production] [in all cities]",
                    "[+1 Production] from every [Mine]",
                    "[+1 Production] from every [Quarry]"
                ],
            		"requires": ["Skyscrapers","Academy of Sciences"],
                "row": 3,
                "column": 1
            },
            {
                "name": "Communism",
                "uniques": [
                    "[+10]% [Science] [in all cities]"
                ],
            		"requires": ["Skyscrapers","Academy of Sciences","Cultural Revolution"],
                "row": 3,
                "column": 3
            },
            {
                "name": "Iron Curtain",
                "uniques": [
                    "[+11 Production] from each Trade Route",
                    "[+11 Food] from each Trade Route",
                    "[+11 Science] from each Trade Route",
                    "[+11 Happiness] from each Trade Route"
                ],
            		"requires": ["Patriotic War","Academy of Sciences","Cultural Revolution"],
                "row": 3,
                "column": 5
            },
            {
                "name": "People's Army",
                "uniques": [
                    "[+100]% Production when constructing [Military Academy] buildings [in all cities]",
                    "[+100]% Production when constructing [Armory] buildings [in all cities]",
                    "[+2 Science, +2 Culture] from every [Military Academy]",
                    "[+2 Science, +2 Culture] from every [Armory]"
                ],
                "row": 1,
                "column": 5
            },
            {
                "name": "Spaceflight Pioneers",
                "uniques": [
                    "Free [Great Scientist] appears",
                    "Free [Great Engineer] appears",
                    //need implement "Spaceflight Pioneers: May finish Spaceship parts with Great Engineers"
                ],
            		"requires": ["Patriotic War","Cultural Revolution"],
                "row": 3,
                "column": 7
            },
            {
                "name": "Order Complete",
                "uniques": ["[+2 Culture] [in all cities]","[+10]% unhappiness from the number of cities"
                ]
            }
        ]
    },
    {
        "name": "Freedom",
        "era": "Modern era",
        "uniques": [
            "Free Social Policy",
            "Comment [Unlocks [Statue of Liberty]]",
            "Only available <before adopting [Autocracy]>",
		"Only available <after adopting [Liberty]>",
		"Only available <before adopting [World]>",
            "Only available <before adopting [Order]>"
        ],
        "policies": [
            {
                "name": "Avant Garde",
                "uniques": [
                    "[+25]% Great Person generation [in all cities]"
                ],
                "row": 1,
                "column": 1
            },
            {
                "name": "Creative Expression",
                "uniques": [
                    "[+2 Culture] from every [Landmark]"
                ],
                "row": 1,
                "column": 3
            },
            {
                "name": "Covert Action",
                "uniques": [
                    "[+100]% spy effectiveness [City-States]",
                    //Unique for rigging elections
                    "Gain an extra spy"
                ],
                "row": 1,
                "column": 5
            },
            {
                "name": "Capitalism",
                "uniques": [
                    "[+1 Happiness] from every [Market]",
                    "[+1 Happiness] from every [Bank]",
                    "[+1 Happiness] from every [Stock Exchange]"
                ],
            		"requires": ["Avant Garde","Creative Expression","Covert Action"],
                "row": 2,
                "column": 3
            },
            {
                "name": "Universal Suffrage",
                "uniques": [
                    "[-50]% Unhappiness from [Specialists] [in all cities]",
                    "[+50]% Golden Age length"
                ],
            		"requires": ["Universal Healthcare","Creative Expression","Covert Action"],
                "row": 2,
                "column": 5
            },
            {
                "name": "Urbanization",
                "uniques": [
                    "[+2 Production, +2 Science] from every [Windmill]",
                    "[+2 Production, +2 Science] from every [Workshop]",
                    "[+2 Production, +2 Science] from every [Factory]"
                ],
            		"requires": ["Universal Healthcare","Covert Action"],
                "row": 2,
                "column": 7
            },
            {
                "name": "Universal Healthcare",
                "uniques": [
                    "[+100]% Production when constructing [Medical Lab] buildings [in all cities]",
                    "[+100]% Production when constructing [Hospital] buildings [in all cities]",
                    "[+3 Science] from every [Medical Lab]",
                    "[+3 Science] from every [Hospital]",
                    "[+5 Food] [in capital]"
                ],
                "row": 1,
                "column": 7
            },
            {
                "name": "New Deal",
                "uniques": [
                    "[+5 Science] from every [Academy]",
                    "[+5 Production] from every [Manufactory]",
                    "[+5 Production] from every [Citadel]",
                    "[+5 Faith] from every [Holy site]",
                    "[+5 Culture] from every [Landmark]",
                    "[+5 Gold] from every [Customs house]",
                    "[+1 Culture, +1 Science, +1 Faith, +1 Production, +1 Food] from every [Great Improvement]"
                ],
            		"requires": ["Arsenal of Democracy","Capitalism"],
                "row": 3,
                "column": 1
            },
            {
                "name": "Media Culture",
                "uniques": [
                    "[+20]% [Culture] <in cities with a [Broadcast Tower]>"
                ],
            		"requires": ["Arsenal of Democracy","Capitalism","Universal Suffrage"],
                "row": 3,
                "column": 3
            },
            {
                "name": "Treaty Organization",
                "uniques": [
                    "[+1 Production, +1 Gold] from every specialist [in all cities]"
                ],
            		"requires": ["Urbanization","Capitalism","Universal Suffrage"],
                "row": 3,
                "column": 5
            },
            {
                "name": "Arsenal of Democracy",
                "uniques": [
                    "[+25]% Production when constructing [Air] units [in all cities]",
                    "[+25]% Production when constructing [Nuclear Missile] units [in all cities]",
                    "[+25]% Strength for cities",
                    "[Fighter] units gain the [Dogfighting I] promotion",
                    "All newly-trained [Fighter] units [in all cities] receive the [Dogfighting I] promotion"
                ],
            		"requires": ["Avant Garde","Creative Expression"],
                "row": 2,
                "column": 1
            },
            {
                "name": "Space Procurements",
                "uniques": [
                    "May buy [Spaceship part] units with [Gold] [in all cities]"
                ],
            		"requires": ["Urbanization","Universal Suffrage"],
                "row": 3,
                "column": 7
            },
            {
                "name": "Freedom Complete",
                "uniques": ["[+100]% Yield from every [Great Improvement]", "[+50]% Golden Age length","[-20]% unhappiness from the number of cities"
                ]
            }
        ]
    },
    {
        "name": "Autocracy",
        "era": "Industrial era",
        "uniques": [
            "Free Social Policy",
            "Comment [Unlocks [Prora]]",
            "Only available <before adopting [Order]>",
            "Only available <before adopting [Freedom]>"
        ],
        "policies": [
            {
                "name": "Fascism",
                "uniques": [
                    "[+12 Happiness]"
                ],
                "row": 1,
                "column": 3
            },
            {
                "name": "Futurism",
                "uniques": [
                    "Gain [250] [Culture] <(modified by game speed)> <upon gaining a [Great Artist] unit>",
                    "Gain [250] [Culture] <(modified by game speed)> <upon gaining a [Great Engineer] unit>",
                    "Gain [250] [Culture] <(modified by game speed)> <upon gaining a [Great General] unit>"
                ],
                "row": 1,
                "column": 7
            },
            {
                "name": "Industrial Espionage",
                "uniques": [
                    "[+100]% spy effectiveness [in all cities]"
                ],
                "row": 1,
                "column": 1
            },
            {
                "name": "Lightning Warfare",
                "uniques": [
                    "[+1] Movement <for [Gunpowder] units>",
                    "[+1] Movement <for [Armored] units>",
                    "[+1] Movement <for [Great General] units>",
                    "[+1] Movement <for [Worker] units>"
                ],
            		"requires": ["Industrial Espionage","Fascism"],
                "row": 2,
                "column": 1
            },
            {
                "name": "Police State",
                "uniques": [
                    "[+2 Happiness] from every [Courthouse]",
                    "[+2 Happiness] from every [Police Station]",
                    "[+2 Happiness] from every [Constabulary]",
                    "[+50]% Production when constructing [Courthouse] buildings [in all cities]",
                    "[+50]% Production when constructing [Police Station] buildings [in all cities]",
                    "[+50]% Production when constructing [Constabulary] buildings [in all cities]"
                ],
            		"requires": ["Industrial Espionage","Fascism","Iron Fist"],
                "row": 2,
                "column": 3
            },
            {
                "name": "Third Alternative",
                "uniques": [
                    "Double quantity of [Horses] produced",
                    "Double quantity of [Iron] produced",
                    "Double quantity of [Coal] produced",
                    "Double quantity of [Oil] produced",
                    "Double quantity of [Aluminum] produced",
                    "Double quantity of [Uranium] produced",
                    "[+5 Science, +5 Food] [in capital]"
                ],
            		"requires": ["Futurism","Fascism","Iron Fist"],
                "row": 2,
                "column": 5
            },
            {
                "name": "Mobilization",
                "uniques": [
                    "[Gold] cost of purchasing [All] units [-25]%",
                    "[-25]% maintenance costs <for [All] units>"
                ],
            		"requires": ["Futurism","Iron Fist"],
                "row": 2,
                "column": 7
            },
            {
                "name": "Total War",
                "uniques": [
                    "[+25]% Production when constructing [Military] units [in all cities]",
                    "New [Military] units start with [15] Experience [in all cities]"
                ],
            		"requires": ["Lightning Warfare","Police State"],
                "row": 3,
                "column": 1
            },
            {
                "name": "Cult of Personality",
                "uniques": [
                    "[+20]% [Culture] [in all cities]"
                ],
            		"requires": ["Lightning Warfare","Police State","Third Alternative"],
                "row": 3,
                "column": 3
            },
            {
                "name": "Gunboat Diplomacy",
                "uniques": [
                    "Resting point for Influence with City-States is increased by [25]"
                ],
            		"requires": ["Mobilization","Police State","Third Alternative"],
                "row": 3,
                "column": 5
            },
		
            {
                "name": "Iron Fist",
                "uniques": [
                    "Earn [100]% of killed [Military] unit's [Strength] as [Culture]",
                    "Earn [100]% of killed [Military] unit's [Strength] as [Science]",
                    "Earn [100]% of killed [Military] unit's [Strength] as [Gold]",
                    "[+50]% XP gained from combat <for [non-[Air]] units>"
                ],
                "row": 1,
                "column": 5
            },
            {
                "name": "Clausewitz's Legacy",
                "uniques": [
                    "[+25]% Strength <for [All] units> <for [50] turns>"
                ],
            		"requires": ["Mobilization","Third Alternative"],
                "row": 3,
                "column": 7
            },
            {
                "name": "Autocracy Complete",
                "uniques": ["[+25]% Strength <when attacking> <for [Military] units> <for [50] turns>","[+20]% unhappiness from the number of cities"
                ]
            }
        ]
    },
]
