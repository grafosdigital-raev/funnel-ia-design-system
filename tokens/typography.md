# Typography Tokens

## Families
- Primary sans: **Inter**
- Editorial accent: **Playfair Display Italic**

## Rules
- Maximum two families per artifact.
- Inter handles interface, body and most headlines.
- Playfair Display Italic is reserved for emotional/editorial turns, tension or human truth.
- Avoid decorative type for technology signaling.

## Hierarchy principles
- Strong scale contrast.
- Large direct headlines.
- Short body paragraphs.
- Generous line-height and breathing room.
- Readability outranks visual novelty.

## Initial scale
These are starting tokens and should be validated in real builds.

- display-xl: clamp(3rem, 8vw, 7rem)
- display-lg: clamp(2.5rem, 6vw, 5rem)
- h1: clamp(2.25rem, 5vw, 4rem)
- h2: clamp(1.75rem, 4vw, 3rem)
- h3: clamp(1.35rem, 2.5vw, 2rem)
- body-lg: 1.125rem
- body: 1rem
- small: 0.875rem

Do not treat the initial scale as immutable until validated against production evidence.
