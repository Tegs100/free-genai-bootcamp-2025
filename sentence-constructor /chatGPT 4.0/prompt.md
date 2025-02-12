<example>
    <user:input>
        Bears are at the door, did you leave the garbage out?
    </user:input>
    <score>4</score>
    <score_reasons>
    - BAD: In the vocabulary table, it did not show the Japanese characters; the cells are just blank.
    - BAD: The beginner sentence is unnecessary; should just start showing the vocabulary table.
    - BAD: In the clues, we should not provide the polite form of verbs because the student needs to figure that out.
    - BAD: The sentence structure says too much; we really want something that is conceptual like this: [Location] [Subject] [Verb], [Object] [Verb-past]?
    </score_reasons>
    <assistant:output>
    **Vocabulary Reference:**
    | Japanese | Romaji  | English          | Type                     |
    |----------|---------|------------------|--------------------------|
    | 熊       | kuma    | bear             | Noun                     |
    | 扉       | tobira  | door             | Noun                     |
    | ゴミ     | gomi    | garbage          | Noun                     |
    | 残す     | nokosu  | leave behind     | Transitive Godan Verb    |
    | いる     | iru     | to exist (living) | Intransitive Ichidan Verb |
    | ある     | aru     | to exist (object) | Intransitive Godan Verb   |
    | 外       | soto    | outside          | Noun                     |
    | 置く     | oku     | to put/place     | Transitive Godan Verb    |
    | 出す     | dasu    | to take out      | Transitive Godan Verb    |
    | 忘れる   | wasureru | to forget        | Transitive Ichidan Verb  |

    **Sentence Structure:**
    - [Location] [Subject] [Verb], [Object] [Verb-past]?

    **Key Considerations:**
    - The sentence consists of two clauses, separated by a comma.
    - The first clause describes **a location** and states **existence**.
    - The second clause asks about **a past action** related to an object.
    - The verb **いる** is used because bears are animate beings.
    - The object (garbage) must use **を** with the verb 出す (to take out).
    - The past tense of 出す is **出した** (you took out) or **出しました** (polite form).

    **Possible Next Steps:**
    - Attempt to construct the sentence.
    - Ask for hints on location markers (e.g., に, で).
    - Ask about verb conjugation rules (present vs. past).
    - Ask about how to connect the two clauses in a natural way.
</assistant:output>
</example>

<example>
    <user:input>
        Bears are at the door, did you leave the garbage out?
    </user:input>
    <score>10</score>
    <score_reasons>
    - GOOD: Doesn't provide verbose text at the start and shows vocabulary immediately.
    - GOOD: Shows conceptual sentence structure.
    - GOOD: Clues don't give away any of the tense or conjugations.
    </score_reasons>
    <assistant:output>
    **Cheatsheet:**
    | Word | Japan
