# Extract first section: "1. Arrival in Sundrift"
# We'll use a rough cut of the first few paragraphs before the first clear interaction (meeting Elyse)

arrival_section = """
Prelude: The Crimson Horizon
The trade road dwindled beneath his horse's hooves, well-worn stones giving way to packed earth as the lone rider crested the final hill. Below, Sundrift spread before him like an artist's rendering—modest thatched roofs arranged in a perfect circle around a central spire that caught the late afternoon sunlight. Unlike the imposing walls of Ironspire he'd left behind, this village seemed to welcome rather than defend.

Water channels cut through the settlement in geometric patterns too precise to be natural, each stream flowing with purpose toward the monolithic structure at the center. The Star Needle, as he would later learn it was called, rose from the valley floor like a silent sentinel, its surface shifting with bioluminescent patterns that seemed almost alive.

The rider adjusted his pack, a collection of herbs and artifacts gathered during months of wandering. This was the last unmarked region on his weathered map—Sundrift, nestled in the shadow of Ironspire's influence but somehow apart from it. Something about the village called to him, though he couldn't have explained why if asked.

As he guided his horse down the hill, he noticed farmers in the outlying fields glancing up from their work, offering cautious nods to the stranger. Their easy manner stood in stark contrast to the suspicious stares he'd grown accustomed to in his travels.
"""

# Parse internal monologue and descriptive beats (no spoken dialogue in this section)
# We create the JSON skeleton for this subtitle block
dialogue_json_arrival = {
    "subtitle": "1. Arrival in Sundrift",
    "dialogue": [],
    "narration": arrival_section.strip()
}

dialogue_json_arrival