# Treaty of Waitangi

A small Victoria 3 mod to support playing as New Zealand through a handful of events centered around the historical Treaty of Waitangi.

## Goal

The goal of the mod is simply to allow playing as New Zealand without resorting to switching countries or releasing subjects in an unnatural way. The mod is not intended to be a full New Zealand flavor pack, but includes just enough content for the creation of New Zealand to occur on a vaguely historical timeline and properly involve all three affected countries; Great Britain, New South Wales, and United Tribes, whether they are controlled by the AI or by players. The aim is to give as close to a base-game experience as possible, and provide a proof of concept for how the base game could include a playable New Zealand without an amount of content that would demand an Immersion Pack.

## Features

- History
	- United Tribes no longer starts as a subject of Great Britain, but has a Guarantee of Independence from a treaty, _He Whakaputanga_, representing the historical Declaration of the Independence of New Zealand.
	- North Island and South Island are no longer homelands for the Australian culture.
	- Western Australia no longer starts with a claim on North Island, and New South Wales now does.
	- A Great Britain controlled by AI starts with the Protect goal towards United Tribes.
- Decisions
	- **Secure Sovereignty over New Zealand** – As Great Britain, form the colony of New Zealand out of New South Welsh states in New Zealand. When controlled by AI, Great Britain will use the decision on or shortly after 2 February, 1840.
- Events
	- **The Treaty of Waitangi** – Triggered for Great Britain by the _Secure Sovereignty over New Zealand_ decision. Gives a player the option to play as the newly established colony of New Zealand.
	- **Te Tiriti o Waitangi** – Triggered for the United Tribes by the _Secure Sovereignty over New Zealand_ decision. Gives the option to accept annexation by New Zealand, or refuse and stay independent. When controlled by AI, the United Tribes will accept the treaty.
	- **The Colony of New Zealand** – Triggered for New South Wales by the _Secure Sovereignty over New Zealand_ decision. Gives a player the option to play as the newly established colony of New Zealand.
- Countries
	- **New Zealand** – New Zealand gets a new primary culture, _New Zealander_, and a new map color, black.
- Cultures
	- **New Zealander** – A distinct culture for New Zealand based on the Australian culture but with a new set of names derived from historical data.
- Discrimination traits
	- **Treaty of Waitangi** – A tradition trait added to the New Zealander and Māori cultures if United Tribes accepts the Treaty of Waitangi.
- Law amendments
	- **Treaty of Waitangi** – Grants a bonus to acceptance from shared tradition traits, giving Māori pops with the __Treaty of Waitangi__ tradition trait enough acceptance for level IV if they are Animist, or level III if they are Protestant. Added to New Zealand's citizenship law if United Tribes accepts the Treaty of Waitangi. The amendment is sponsored by the Devout, to reflect the role of Henry Williams, and has Subjecthood as its parent law.
- Historical characters
	- **William Hobson** – The historical first Governor of New Zealand. A Moderate member of the Armed Forces interest group with the Military Governor, Brave and Sickly traits. He will become the ruler of New Zealand if the _Secure Sovereignty over New Zealand_ decision is taken before his historical date of death, 10 September 1842.
- Journal Entries
	- The _Federate Australia_ journal entries no longer include or require New Zealand states.

## Historical Accuracy

- The _Secure Sovereignty over New Zealand_ decision represents the Colonial Office's appointment of William Hobson to obtain Māori recognition of British sovereignty over New Zealand in 1839, the signing of the Treaty of Waitangi in 1840, and the creation of the separate Colony of New Zealand in 1841. A player can activate the decision at any time but the AI will activate it on or shortly after the historical date for the signing of the Treaty of Waitangi.
- All event flavor text and option button labels are pulled from historical sources and paraphrased or quoted verbatim, with some dynamic substitutions for things like the British monarch's name and gender. Sources include quotes from participants in the signing, Lord Normanby's [instructions](https://www.treatyofwaitangi.net.nz/LordNormanbysBrief.html) to William Hobson,  an 1841 [address](https://gazette.slv.vic.gov.au/images/1841/N/general/46.pdf) by Governor George Gipps to the New South Wales Legislative Council, and an 1845 [debate](https://hansard.parliament.uk/commons/1845-06-19/debates/4e9b11cf-4610-4a5d-abb6-da669fa9d928/NewZealand—AdjournedDebate(ThirdNight)) in the British Parliament regarding New Zealand.
- The _Te Tiriti o Waitangi_ event uses the terms "covenant" and "governorship" to attempt to capture the Māori interpretation of the meaning of the treaty.
- The _Treaty of Waitangi_ tradition trait and law amendment increase the acceptance of the Māori to reflect historical treatment that was better than what their acceptance level in the base game would otherwise imply, but is not intended to suggest fair treatment by the authorities. Under the starting laws of New South Wales that New Zealand inherits Animist Māori will only reach acceptance level IV with the amendment and trait, while Protestant Māori can reach level III. Additionally, the AI is configured to remove the amendment if they increase their autonomy and have an interest group in government that supports Racial Segregation.
- The _New Zealander_ first name lists are the [most popular](https://figure.nz/table/rR1v0D0NkL88L8pN) names from 1848–2018 excluding names not found in the [top 10](https://catalogue.data.govt.nz/dataset/baby-name-popularity-over-time) of any year between 1900–1918. The surname list is the most common surnames found in Auckland Museum Cenotaph [data](https://github.com/AucklandMuseum/Collection-Data/blob/master/Cenotaph%20Data/WW1_Data.tsv) for World War I. The noble surnames are posh-sounding names drawn from the [list](https://www3.parliament.nz/en/visit-and-learn/mps-and-parliaments-1854-onwards/members-of-the-new-zealand-legislative-council-1853-to-1950/) of members of the New Zealand Legislative Council during the period where they were appointed for life.

## AI use

No AI generated assets or text are included in the mod. Codex was used to help in development and the parsing of name data, but all scripting has been reviewed and amended by hand.
