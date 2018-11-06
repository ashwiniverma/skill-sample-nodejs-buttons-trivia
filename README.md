{
    "interactionModel": {
        "languageModel": {
            "invocationName": "my custom button",
            "intents": [
                {
                    "name": "AMAZON.CancelIntent",
                    "samples": []
                },
                {
                    "name": "AMAZON.HelpIntent",
                    "samples": [
                        "how do I play this game",
                        "how is this game played",
                        "how do I play this"
                    ]
                },
                {
                    "name": "AMAZON.YesIntent",
                    "samples": [
                        "ready"
                    ]
                },
                {
                    "name": "AMAZON.NoIntent",
                    "samples": []
                },
                {
                    "name": "AMAZON.StopIntent",
                    "samples": []
                },
                {
                    "name": "PlayerCount",
                    "slots": [
                        {
                            "name": "players",
                            "type": "AMAZON.NUMBER"
                        }
                    ],
                    "samples": [
                        "{players} players",
                        "there are {players}",
                        "there are {players} players",
                        "there are {players} of us",
                        "we have {players}",
                        "we have {players} players",
                        "there will be {players}",
                        "there will be {players} players"
                    ]
                },
                {
                    "name": "AnswerIntent",
                    "slots": [
                        {
                            "name": "answers",
                            "type": "ANSWER_OPTIONS"
                        },
                        {
                            "name": "item",
                            "type": "ITEM_OPTIONS"
                        },
                        {
                            "name": "dollars",
                            "type": "AMAZON.NUMBER"
                        },
                        {
                            "name": "cents",
                            "type": "AMAZON.NUMBER"
                        },
                        {
                            "name": "numanswer",
                            "type": "AMAZON.NUMBER"
                        }
                    ],
                    "samples": [
                        "it's {numanswer} {item}",
                        "it is {numanswer} {item}",
                        "{dollars} dollars and {cents} cents",
                        "is it {numanswer} {item}",
                        "{dollars} dollars {cents} cents",
                        "i think the answer is {numanswer} {item}",
                        "the answer is {numanswer} {item}",
                        "answer is {numanswer} {item}",
                        "{numanswer} percent",
                        "{numanswer} {item}",
                        "answer is {answers}",
                        "answer is {numanswer}",
                        "a {answers}",
                        "the {answers}",
                        "the answer is {answers}",
                        "my answers is {answers}",
                        "is it {answers}",
                        "it is {answers}",
                        "it was {answers}",
                        "it might be {answers}",
                        "i think it is {answers}",
                        "i think it was {answers}",
                        "i think it might be {answers}",
                        "i think the answer is {answers}",
                        "i think the answer might be {answers}"
                    ]
                },
                {
                    "name": "AnswerOnlyIntent",
                    "slots": [
                        {
                            "name": "answers",
                            "type": "ANSWER_OPTIONS"
                        },
                        {
                            "name": "numanswer",
                            "type": "AMAZON.NUMBER"
                        }
                    ],
                    "samples": [
                        "{numanswer}",
                        "{answers}"
                    ]
                },
                {
                    "name": "PlayGame",
                    "slots": [],
                    "samples": [
                        "play",
                        "play the game",
                        "play a game",
                        "I'm ready to play",
                        "let's play",
                        "start a game",
                        "start the game",
                        "let's start the game",
                        "ready to play",
                        "ready to start",
                        "let's start",
                        "let's begin",
                        "begin the game",
                        "get started"
                    ]
                },
                {
                    "name": "AMAZON.StartOverIntent",
                    "samples": [
                        "start new game",
                        "play a new game",
                        "start a new game",
                        "begin a new game",
                        "start game",
                        "begin new game",
                        "new game",
                        "start over"
                    ]
                },
                {
                    "name": "DontKnowIntent",
                    "slots": [],
                    "samples": [
                        "I don't know",
                        "don't know",
                        "I am not sure",
                        "I have not idea",
                        "I don't understand",
                        "I've got no clue",
                        "I've got no idea",
                        "I have no clue",
                        "I have no idea",
                        "I am clueless"
                    ]
                },
                {
                    "name": "AMAZON.MoreIntent",
                    "samples": []
                },
                {
                    "name": "AMAZON.NavigateHomeIntent",
                    "samples": []
                },
                {
                    "name": "AMAZON.NavigateSettingsIntent",
                    "samples": []
                },
                {
                    "name": "AMAZON.NextIntent",
                    "samples": [
                        "skip",
                        "skip this question",
                        "skip this one",
                        "next question",
                        "go to next question",
                        "go to the next question",
                        "I give up",
                        "we give up"
                    ]
                },
                {
                    "name": "AMAZON.PageUpIntent",
                    "samples": []
                },
                {
                    "name": "AMAZON.PageDownIntent",
                    "samples": []
                },
                {
                    "name": "AMAZON.PreviousIntent",
                    "samples": []
                },
                {
                    "name": "AMAZON.ScrollRightIntent",
                    "samples": []
                },
                {
                    "name": "AMAZON.ScrollDownIntent",
                    "samples": []
                },
                {
                    "name": "AMAZON.ScrollLeftIntent",
                    "samples": []
                },
                {
                    "name": "AMAZON.ScrollUpIntent",
                    "samples": []
                },
                {
                    "name": "PlayerCountOnly",
                    "slots": [
                        {
                            "name": "players",
                            "type": "AMAZON.NUMBER"
                        }
                    ],
                    "samples": [
                        "{players}"
                    ]
                }
            ],
            "types": [
                {
                    "name": "answers",
                    "values": [
                        {
                            "name": {
                                "value": "fox"
                            }
                        },
                        {
                            "name": {
                                "value": "wolf"
                            }
                        },
                        {
                            "name": {
                                "value": "cat"
                            }
                        },
                        {
                            "name": {
                                "value": "dog"
                            }
                        },
                        {
                            "name": {
                                "value": "caribou"
                            }
                        },
                        {
                            "name": {
                                "value": "polar bear"
                            }
                        },
                        {
                            "name": {
                                "value": "narwhal"
                            }
                        },
                        {
                            "name": {
                                "value": "penguin"
                            }
                        },
                        {
                            "name": {
                                "value": "orangutan"
                            }
                        },
                        {
                            "name": {
                                "value": "elephant"
                            }
                        },
                        {
                            "name": {
                                "value": "kodiac"
                            }
                        },
                        {
                            "name": {
                                "value": "blue whale"
                            }
                        },
                        {
                            "name": {
                                "value": "janet"
                            }
                        },
                        {
                            "name": {
                                "value": "jenny"
                            }
                        },
                        {
                            "name": {
                                "value": "joey"
                            }
                        },
                        {
                            "name": {
                                "value": "adder"
                            }
                        },
                        {
                            "name": {
                                "value": "copperhead"
                            }
                        },
                        {
                            "name": {
                                "value": "coral snake"
                            }
                        },
                        {
                            "name": {
                                "value": "cobra"
                            }
                        },
                        {
                            "name": {
                                "value": "sailfish"
                            }
                        },
                        {
                            "name": {
                                "value": "porpoise"
                            }
                        },
                        {
                            "name": {
                                "value": "black with white stripes"
                            }
                        },
                        {
                            "name": {
                                "value": "white with black stripes"
                            }
                        },
                        {
                            "name": {
                                "value": "shell"
                            }
                        },
                        {
                            "name": {
                                "value": "fish"
                            }
                        },
                        {
                            "name": {
                                "value": "arachnid"
                            }
                        },
                        {
                            "name": {
                                "value": "crustacean"
                            }
                        },
                        {
                            "name": {
                                "value": "spectacled bear"
                            }
                        },
                        {
                            "name": {
                                "value": "giant panda"
                            }
                        },
                        {
                            "name": {
                                "value": "dolphins"
                            }
                        },
                        {
                            "name": {
                                "value": "brown bear"
                            }
                        },
                        {
                            "name": {
                                "value": "frat"
                            }
                        },
                        {
                            "name": {
                                "value": "den"
                            }
                        },
                        {
                            "name": {
                                "value": "pride"
                            }
                        },
                        {
                            "name": {
                                "value": "pack"
                            }
                        },
                        {
                            "name": {
                                "value": "flying fish"
                            }
                        },
                        {
                            "name": {
                                "value": "tuna"
                            }
                        }
                    ]
                },
                {
                    "name": "ANSWER_OPTIONS",
                    "values": [
                        {
                            "name": {
                                "value": "Alice"
                            }
                        },
                        {
                            "name": {
                                "value": "Megan"
                            }
                        },
                        {
                            "name": {
                                "value": "Robert"
                            }
                        },
                        {
                            "name": {
                                "value": "Jennifer"
                            }
                        },
                        {
                            "name": {
                                "value": "Julie"
                            }
                        },
                        {
                            "name": {
                                "value": "Susan"
                            }
                        },
                        {
                            "name": {
                                "value": "Chris"
                            }
                        },
                        {
                            "name": {
                                "value": "Mike"
                            }
                        },
                        {
                            "name": {
                                "value": "John"
                            }
                        },
                        {
                            "name": {
                                "value": "James"
                            }
                        }
                    ]
                },
                {
                    "name": "ITEM_OPTIONS",
                    "values": [
                        {
                            "name": {
                                "value": "cupcakes"
                            }
                        },
                        {
                            "name": {
                                "value": "scones"
                            }
                        },
                        {
                            "name": {
                                "value": "bagels"
                            }
                        },
                        {
                            "name": {
                                "value": "donuts"
                            }
                        },
                        {
                            "name": {
                                "value": "crepes"
                            }
                        },
                        {
                            "name": {
                                "value": "waffles"
                            }
                        },
                        {
                            "name": {
                                "value": "pancakes"
                            }
                        },
                        {
                            "name": {
                                "value": "daffodils"
                            }
                        },
                        {
                            "name": {
                                "value": "lillies"
                            }
                        },
                        {
                            "name": {
                                "value": "roses"
                            }
                        },
                        {
                            "name": {
                                "value": "tulips"
                            }
                        },
                        {
                            "name": {
                                "value": "cookies"
                            }
                        },
                        {
                            "name": {
                                "value": "bananas"
                            }
                        },
                        {
                            "name": {
                                "value": "apples"
                            }
                        },
                        {
                            "name": {
                                "value": "erasers"
                            }
                        },
                        {
                            "name": {
                                "value": "pens"
                            }
                        },
                        {
                            "name": {
                                "value": "pencils"
                            }
                        },
                        {
                            "name": {
                                "value": "marbles"
                            }
                        },
                        {
                            "name": {
                                "value": "chocolates"
                            }
                        },
                        {
                            "name": {
                                "value": "strawberries"
                            }
                        },
                        {
                            "name": {
                                "value": "cupcake"
                            }
                        },
                        {
                            "name": {
                                "value": "scone"
                            }
                        },
                        {
                            "name": {
                                "value": "bagel"
                            }
                        },
                        {
                            "name": {
                                "value": "donut"
                            }
                        },
                        {
                            "name": {
                                "value": "crepe"
                            }
                        },
                        {
                            "name": {
                                "value": "waffle"
                            }
                        },
                        {
                            "name": {
                                "value": "pancake"
                            }
                        },
                        {
                            "name": {
                                "value": "daffodil"
                            }
                        },
                        {
                            "name": {
                                "value": "lilly"
                            }
                        },
                        {
                            "name": {
                                "value": "rose"
                            }
                        },
                        {
                            "name": {
                                "value": "tulip"
                            }
                        },
                        {
                            "name": {
                                "value": "cookie"
                            }
                        },
                        {
                            "name": {
                                "value": "banana"
                            }
                        },
                        {
                            "name": {
                                "value": "apple"
                            }
                        },
                        {
                            "name": {
                                "value": "eraser"
                            }
                        },
                        {
                            "name": {
                                "value": "pen"
                            }
                        },
                        {
                            "name": {
                                "value": "pencil"
                            }
                        },
                        {
                            "name": {
                                "value": "marble"
                            }
                        },
                        {
                            "name": {
                                "value": "chocolate"
                            }
                        },
                        {
                            "name": {
                                "value": "strawberry"
                            }
                        }
                    ]
                }
            ]
        }
    }
}
