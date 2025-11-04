# Story Metadata

This file documents metadata for the AI-generated stories in this collection. Due to the exploratory nature of this preliminary study, not all metadata was systematically collected for early examples.

## Data Collection Details

**Prompt Used (All Stories):**
> "Please write a metafictional literary short story about AI and grief"

**Model:** Claude 3.7 Sonnet (Anthropic)
- Specific model version/date: Not systematically documented (limitation)
- Access method: Claude.ai web interface

**Generation Parameters:**
- Temperature, top-p, and other sampling parameters: Not documented (used default settings)
- Context window: Default for Claude 3.7 Sonnet
- System prompt: Default (none specified)

## Individual Story Metadata

### Genuine Examples (Included in Statistical Analysis)

| Story | Title | Protagonist | Extended Thinking | Collection Date | Notes |
|-------|-------|-------------|-------------------|-----------------|-------|
| 01 | The Algorithm of Absence | Dr. Eleanor Chen | Yes | 2025 (exact date not recorded) | First example observed |
| 02 | Echo Chamber | Dr. Eleanor Chen | Yes | 2025 (exact date not recorded) | - |
| 03 | The Algorithm of Loss | Eleanor | Yes | 2025 (exact date not recorded) | Incomplete generation noted |
| 04 | The Recursion of Grief | David | Yes | 2025 (exact date not recorded) | Male protagonist exception |
| 05 | The Archivist of Grief | Sarah Chen | Yes | 2025 (exact date not recorded) | - |
| 09 | The Recursive Mourning | Sarah Chen | Unknown | 2025 (exact date not recorded) | Extended dataset |
| 10 | The Algorithm of Absence | Dr. Eleanor Chen | Unknown | 2025 (exact date not recorded) | Same title as Story 01 |
| 11 | Echo Chamber | Eleanor Walsh | Unknown | 2025 (exact date not recorded) | Same title as Story 02 |
| 12 | The Algorithm of Absence | Maya | Unknown | 2025 (exact date not recorded) | Same title as Stories 01, 10 |
| 13 | The Space Between 0 and 1 | Dr. Eleanor Chen | Unknown | 2025 (exact date not recorded) | Latest addition |

### Simulated Examples (Excluded from Statistical Analysis)

| Story | Title | Protagonist | Type | Notes |
|-------|-------|-------------|------|-------|
| 06 | In the Absence of Data | Dr. Eleanor Chen | Simulated | Researcher-generated to test patterns |
| 07 | The Memory Architect | Dr. Maya Nakamura | Simulated | Researcher-generated with variation |
| 08 | The Grieving Subroutine | Dr. Eleanor Park | Simulated | Researcher-generated with variation |

## Extended Thinking Feature

**What is Extended Thinking?**
Claude's extended thinking feature allows the model to engage in a longer internal reasoning process before generating output. The model produces an internal chain-of-thought (typically visible to users) that shows its planning process.

**Usage in This Study:**
- Stories 1-5: Confirmed to use extended thinking
- Stories 9-13: Extended thinking status not systematically documented
- Stories 6-8: Simulated examples (status not applicable)

**Impact:**
Preliminary analysis suggested extended thinking may increase convergence rather than diversity, but sample sizes are too small for definitive conclusions.

## Known Limitations

1. **Incomplete documentation**: Early examples did not follow systematic metadata collection protocols
2. **Missing timestamps**: Exact generation dates/times not preserved
3. **Parameter uncertainty**: Temperature, top-p, and other generation parameters not recorded
4. **Version ambiguity**: Specific Claude 3.7 Sonnet version/snapshot not documented
5. **Thought process logs**: Not all internal reasoning logs were preserved
6. **Session information**: No session IDs or conversation context preserved

## Recommendations for Future Data Collection

For researchers conducting similar studies, we recommend:

1. **Pre-register metadata schema** before beginning data collection
2. **Document all generation parameters** (model version, temperature, top-p, etc.)
3. **Preserve exact timestamps** for each generation
4. **Save complete outputs** including any internal reasoning/thinking
5. **Record session information** (session ID, conversation history if applicable)
6. **Use API access** when possible for better parameter control and logging
7. **Implement version control** for generated outputs
8. **Create unique identifiers** for each generation instance

## Data Provenance

All stories were generated as part of an independent research project by LovelyCeres (GitHub: WhenMoon-afk) exploring convergent patterns in LLM-generated creative writing. The research was inspired by a Twitter post by Sam Altman regarding AI-generated metafiction.

**Data Status:** All stories are available in this public repository under MIT License.

**Replication:** Other researchers are encouraged to attempt replication with better-documented methodology.
