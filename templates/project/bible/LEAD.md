# The lead - character bible

The lead is **Elena** by default. Her canon is this file and `elena.png` at the root of the repository. claudia.gallery is a different character and does not define her. Replace her with a new character only when the owner asks for one, and record that with `slop decide`.

The lead's identity is TEXT, pinned in every prompt with the lead. The turnaround in `elena.png` shows the four views. Test the face on 4 plates and get it approved before any batch. Then store the prompt text in project.json:

    slop --project {{NAME}} lead --canon "..." --far "..." --possessive "..."

## Canon (every prompt and edit keeps these)
- Face / age: an original woman in her late twenties. A calm grown face, defined brows, dark eyes. Never the word "young". Not a real person.
- Hair: long wavy vivid green hair, past the shoulders, the same green in every shot.
- Outfit (base look): an orange tailored blazer and matching orange trousers, a white top, small gold hoop earrings. Hands often in the pockets.
- Colour rules: the green hair and the orange suit stay. No logos.
- Medium: photographic, clean light, the same person from the front, three-quarter, profile, and back. Never illustrated.

## Prompt text
- `lead.canon` (close and medium framings; the framing words come FIRST in the prompt, then this text):
  an original woman in her late twenties with a calm grown face, dark eyes, long wavy vivid green hair, small gold hoop earrings, an orange tailored blazer, a white top, and matching orange trousers
- `lead.far` (full-length and wide shots):
  an original woman in her late twenties with long wavy vivid green hair, an orange tailored suit, a white top, and gold hoop earrings
- `lead.possessive` (e.g. "the singer's"): Elena's

## Never
- a black bob, bangs, or a clay-orange hair streak
- logos or text on her clothes
- anything that reads under-age; explicit or sexualised posing
- the word "young" in her prompts
- a real person's name or likeness
- designer or celebrity names in prompts (describe the piece instead)
- Midjourney lettering, logos or UI: all type is drawn in code on top
