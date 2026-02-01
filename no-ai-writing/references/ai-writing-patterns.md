# AI Writing Patterns — Detailed Reference

Full catalog of identifiable AI writing patterns to avoid. Organized by category.

## Table of Contents

1. Vocabulary
2. Symbolism, Legacy, and Importance Inflation
3. Notability and Attribution Inflation
4. Superficial Analyses (Participial Phrases)
5. Promotional and Advertisement Language
6. Didactic Disclaimers
7. Section Summaries and Conclusions
8. Challenge-and-Future-Outlook Formula
9. Negative Parallelisms
10. Rule of Three
11. Vague Attribution
12. Elegant Variation
13. False Ranges
14. Formatting Tells
15. Social Media Presence Mentions
16. Leads Treating Titles as Proper Nouns

---

## 1. Vocabulary

These words are statistically overrepresented in LLM output compared to pre-2022 human text. They tend to co-occur — where there is one, others usually follow.

**High-signal words (strong tells when clustered):**
aligns/aligning with, crucial, delve/delves/delving, emphasizing, enduring, enhance/enhances/enhancing, fostering, garnered/garnering, highlight/highlighted/highlighting/highlights (as verb), interplay, intricate/intricacies, pivotal, showcase/showcased/showcases/showcasing, tapestry (abstract), testament, underscore/underscored/underscores/underscoring, landscape (abstract)

**High-signal phrases:**
stands/serves as, is a testament/reminder, plays a vital/significant/crucial/pivotal role, underscores/highlights its importance/significance, reflects broader, symbolizing its ongoing/enduring/lasting impact, key turning point, indelible mark, deeply rooted, profound heritage, steadfast dedication, rich tapestry, continues to captivate, groundbreaking (figurative), stunning natural beauty, enduring/lasting legacy, nestled, in the heart of, boasts a...

**Remediation:** Replace with plainer alternatives or cut entirely. "Plays a pivotal role" → "matters for" or just state the relationship directly. "Rich tapestry of" → delete and name the specific things. "Garnered attention" → "attracted notice" or "got coverage in [specific source]."

## 2. Symbolism, Legacy, and Importance Inflation

LLMs inflate the importance of subjects by attaching claims about broader significance to mundane facts. Even etymology or population data gets treated as symbolic.

**Pattern:** [mundane fact] + [claim about what it represents/symbolizes/reflects]

**Bad:** "This etymology highlights the enduring legacy of the community's resistance and the transformative power of unity in shaping its identity."
**Better:** Just state the etymology. If the legacy claim is sourced, attribute it to the source.

**Bad:** "The founding of Idescat represented a significant shift toward regional statistical independence... This initiative was part of a broader movement across Spain to decentralize administrative functions."
**Better:** "Idescat was established in 1989 as part of Spain's decentralization of administrative functions."

Watch for: any sentence where the subject is an ordinary fact and the predicate claims it "highlights," "reflects," "symbolizes," "underscores," or "represents" something grand.

## 3. Notability and Attribution Inflation

LLMs try to prove a subject's importance by listing media outlets or asserting "independent coverage" — often echoing Wikipedia's own guideline language.

**Tells:**
- Listing outlets without saying what they reported: "featured in Vogue, Wired, Toronto Star, and other media"
- Using Wikipedia policy language: "independent coverage," "local/regional/national media outlets"
- Painstaking in-body attribution of trivial or uncontroversial facts: "According to filings at Companies House, the company reported annual revenue of..."

**Fix:** If coverage matters, say what the source reported. Don't list outlets as proof of notability. Don't attribute uncontroversial facts with "According to..." when a simple inline citation suffices.

## 4. Superficial Analyses (Participial Phrases)

The telltale "-ing" phrase appended to sentences, where inanimate facts or events are made the subject of verbs like "highlighting," "ensuring," "reflecting."

**The problem:** A fact cannot "highlight" something. A building cannot "underscore" its own importance. This is a disembodied narrator inserting opinion disguised as description.

**Bad:** "Its bilingual monument sign, with inscriptions in both English and Spanish, underscores its role in bringing together Latter-day Saints from the United States and Mexico."
**Better:** "Its monument sign has inscriptions in both English and Spanish."

**Bad:** "Douera enjoys close proximity to the capital city, Algiers, further enhancing its significance as a dynamic hub of activity and culture."
**Better:** "Douera is near Algiers."

**Words that trigger this pattern:** ensuring, highlighting, emphasizing, reflecting, underscoring, showcasing, aligns with, contributing to.

## 5. Promotional and Advertisement Language

LLMs slip into the register of press releases, travel brochures, and TV commercials — especially for topics involving cultural heritage, tourism, companies, or products.

**Tells:**
- "Nestled within the breathtaking region of..."
- "Offers visitors a fascinating glimpse into the diverse tapestry of..."
- "Gateway to [region's] diverse attractions, seamlessly connecting..."
- "Powerful emotional presence," "refined dynamism," "cohesive and elegant design"
- "Dedication to craftsmanship and historical reverence"

**Fix:** Strip adjectives that evaluate rather than describe. State facts. Let the reader form their own impression.

## 6. Didactic Disclaimers

LLMs tell the reader what's important to remember, as if lecturing a student.

**Tells:**
- "It's important/critical/crucial to note/remember/consider..."
- "It is crucial to differentiate..."
- "May vary depending on jurisdiction/locale..."
- Safety disclaimers inserted into factual content

**Fix:** Present information directly. If something varies by jurisdiction, state the variation rather than warning about it.

## 7. Section Summaries and Conclusions

LLMs restate the main point at the end of sections or paragraphs — a habit from being trained to generate structured, essay-style output.

**Tells:**
- "In summary, ..."
- "In conclusion, ..."
- "Overall, ..."
- Final sentences that rephrase the opening sentence of the same paragraph
- Entire sections titled "Conclusion" that add no new information

**Fix:** End sections when the information ends. The last sentence should deliver the last piece of content, not a recap.

## 8. Challenge-and-Future-Outlook Formula

A rigid structural pattern found at the end of many LLM articles:

1. "Despite its [positive qualities], [subject] faces challenges..."
2. List of vague challenges
3. "Despite these challenges, [subject] continues to..."
4. Optional: "Future Prospects" section with speculation about how initiatives could help

**Bad:** "Despite its industrial and residential prosperity, Korattur faces challenges typical of urban areas... With its strategic location and ongoing initiatives, Korattur continues to thrive as an integral part of the Ambattur industrial zone."
**Better:** Report the actual challenges with specifics (traffic congestion increased X% since Y; water supply interruptions affect Z neighborhoods). Skip the redemptive ending unless there's concrete evidence of improvement.

## 9. Negative Parallelisms

Overused contrastive constructions:

- "Not only ... but also ..."
- "It is not just about ..., it's ..."
- "Not ... but ..." across multiple sentences for dramatic effect

These are fine in moderation. The problem is frequency — LLMs reach for them constantly.

## 10. Rule of Three

LLMs default to groups of three items in lists, descriptions, and analyses. This makes superficial analyses appear more comprehensive than they are.

**Bad:** "The event features keynote sessions, panel discussions, and networking opportunities."
**Better:** Say something specific about the event rather than listing generic conference components.

**Remediation:** Vary group sizes. Two items or four items can be more natural than always landing on three.

## 11. Vague Attribution

Attributing opinions or claims to unnamed authorities:

- "Has been described as..."
- "Observers have cited..."
- "Some critics argue..."
- "Industry reports suggest..."
- "Due to its unique characteristics, [subject] is of interest to researchers and conservationists"

**Fix:** Name the source, or state the fact without attribution. "Researchers" who? "Industry reports" — which ones?

## 12. Elegant Variation

Driven by repetition penalties, LLMs swap synonyms for the same referent throughout a passage. A person gets called "the protagonist," "the key player," "the eponymous character" in successive sentences.

**Fix:** Repeat the actual name or term. Natural prose uses pronouns and the original term — not a thesaurus of alternatives.

## 13. False Ranges

"From [X] to [Y]" constructions where X and Y aren't on a meaningful scale:

**Bad:** "From problem-solving and tool-making to scientific discovery, artistic expression, and technological innovation..."
**Test:** Can you identify a coherent middle point between X and Y without switching scales? If not, it's a false range.

**Fix:** Just list the items without pretending they form a spectrum.

## 14. Formatting Tells

### Excessive boldface
Don't bold every key term, acronym, or concept on first mention. Bold sparingly for genuine structural emphasis.

### Title case headings
Use sentence case ("Early life and career") not title case ("Early Life And Career") unless the target style guide requires it.

### Inline-header vertical lists
The pattern: bullet/number → **bold heading**: description text. This comes from readmes, fan wikis, and slide decks. Avoid unless the format specifically calls for it.

### Emoji decoration
Never place emojis before section headings or bullet points in professional writing.

### Em dash overuse
LLMs use em dashes where commas, parentheses, or colons would be more natural. Limit to one or two per piece. Watch for the formulaic sales-writing pattern of em dashes emphasizing parallel clauses.

### Curly quotation marks
In plain text and markup contexts, use straight quotes ("...") and straight apostrophes ('), not curly/smart quotes ("...") and curly apostrophes (').

## 15. Social Media Presence Mentions

LLMs insert "maintains an active social media presence" or similar when writing about any entity that uses social media. This phrasing is distinctly AI-generated and rarely appeared on Wikipedia before 2024.

**Fix:** Either omit or describe the specific social media activity with concrete details.

## 16. Leads Treating Titles as Proper Nouns

When writing about a topic whose title is not a proper name (e.g., a list article, a concept), LLMs introduce the title as if it were a real-world entity: "The 'List of songs about Mexico' is a curated compilation of..."

**Fix:** Describe the subject naturally without quoting the title as a proper noun.
