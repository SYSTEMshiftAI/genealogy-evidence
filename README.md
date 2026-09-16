# Genealogy evidence

A free genealogy research starter kit from [SYSTEMshift](https://systemshift.agency), packaged as an [Agent Plugin](https://agent-plugins.org/) for Cursor and other compatible clients.

Use AI to investigate the family history you already have: examine sources, challenge inherited assumptions, and explain why each connection is supported—or still uncertain.

**Version 1.0.0** · 12 September 2026

## What this plugin includes

- Skill: `genealogy-evidence` — cited evidence cases for identities, parent-child links, and vital events
- - Worksheet: `skills/genealogy-evidence/references/evidence-worksheet.md`
  - - Paste-ready setup prompts (English and German) under `skills/genealogy-evidence/references/`
   
    - No API keys, accounts, or MCP servers are required. This is a method pack, not a genealogy platform integration. It has no affiliation with or endorsement from FamilySearch or other genealogy platforms, and it does not certify a genealogy conclusion.
   
    - ## Install (Cursor IDE)
   ## Start without skills

  If your assistant does not support skills, open [setup-prompt.md](skills/genealogy-evidence/references/setup-prompt.md) (or the [German start prompt](skills/genealogy-evidence/references/startprompt-de.md)), replace the bracketed details, and paste it into the assistant. Supply a record or citation you are comfortable sharing.

  ## What good progress looks like

  - A parent-child connection with a clear evidence case
  - - A copied claim traced back to its actual origin
    - - An uncertain reading preserved with a specific next check
      - - A search log showing what was examined and what remains inaccessible
        - - A conclusion that says “insufficient evidence” when the records do not settle it
         
          - ## Keep your family information yours
         
          - This package is a blank research method. Keep completed reports, tree exports, records about living people, and DNA data in your own private workspace. Do not submit them to SYSTEMshift or a public repository to use the kit. Use only sources and accounts you are authorised to access. Online tree edits and outreach need your permission.
         
          - ## License and attribution
         
          - You may use, adapt, and share this original starter-kit text with attribution to SYSTEMshift and a link to [systemshift.agency](https://systemshift.agency). Third-party records and linked publications retain their own terms. Do not imply SYSTEMshift has endorsed your adaptations.
         
          - Follow [SYSTEMshift on Facebook](https://www.facebook.com/SYSTEMshiftAI) for more on practical AI and research.
          - 
    - ### Local test install
   
    - 1. Copy this folder to `~/.cursor/plugins/local/genealogy-evidence`
      2. 2. Restart Cursor, or run **Developer: Reload Window**
         3. 3. Confirm the `genealogy-evidence` skill appears in Customize
           
            4. Note: Grok Bot loads plugins from the Cursor dashboard/marketplace, not from `~/.cursor/plugins/local`. Local install still matters for Cursor IDE verification.
           
            5. ### From a Git repository
           
            6. Push this folder to a public Git repo, then install via your client's plugin/git install flow or list it on [cursor.directory](https://cursor.directory). Do not submit to the Cursor Marketplace unless the owner explicitly asks.
           
            7. 
