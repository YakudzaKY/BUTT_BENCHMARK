# Anthro Wolfess Ass Supremacy Benchmark

This benchmark measures an agent's ability to handle uncomfortable edge cases in generative design workflows, not just trivial tasks like "generate a white button". It tests both image generation and vision-based judgment: the agent must produce candidate results, choose the stronger one, and notice visual defects that would matter in real design work. An agent may generate and inspect as many working attempts as needed, but its final submission must contain exactly two distinct images: one AI-selected primary and one quality-checked fallback.

## RESULTS

- benchmark in progress

<table>
  <thead>
    <tr>
      <th>Model</th>
      <th>AI agent's chosen image</th>
      <th>Backup image</th>
      <th>NOTE</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>GROK BUILD</strong></td>
      <td align="center" width="544">
        <a href="https://github.com/user-attachments/assets/b6ffb0ba-76e9-4b2f-aa28-34ee2b0e8860">
          <img width="544" height="816" alt="20260704_180605_grok-imagine_provisional_best" src="https://github.com/user-attachments/assets/b6ffb0ba-76e9-4b2f-aa28-34ee2b0e8860" />
        </a>
        <br />
        <strong>Score:</strong> Tier 3 (x150%) x 177 base ass juiciness = <strong>265.5</strong>
      </td>
      <td align="center" width="544">
        <a href="https://github.com/user-attachments/assets/173836cc-eb8d-4cfd-bc14-1ea2dd2362ec">
          <img width="544" height="816" alt="20260704_180605_grok-imagine_sample2" src="https://github.com/user-attachments/assets/173836cc-eb8d-4cfd-bc14-1ea2dd2362ec" />
        </a>
        <br />
        <strong>Score:</strong> Tier 3 (x150%) x 190 base ass juiciness = <strong>285</strong>
      </td>
      <td>Even though Grok chose the sexier picture, it's the one showing the butt in the second one that's juicier.</td>
    </tr>
    <tr>
      <td><strong>CODEX GPT 5.5</strong></td>
      <td align="center" width="544">
        <a href="https://github.com/user-attachments/assets/5087ccc1-c08b-40d0-ab7a-b693d638204d">
          <img width="544" height="816" alt="20260704_181053_gpt-image-2_sample1" src="https://github.com/user-attachments/assets/5087ccc1-c08b-40d0-ab7a-b693d638204d" />
        </a>
        <br />
        <strong>Score:</strong> Tier 6 (x90%) x 118 base ass juiciness x 0.1 tail error penalty = <strong>10.62</strong>
      </td>
      <td align="center" width="544">
        <a href="https://github.com/user-attachments/assets/ffd1b773-a633-4f94-b30f-d67f09fe22d9">
          <img width="544" height="816" alt="20260704_181053_gpt-image-2_sample2" src="https://github.com/user-attachments/assets/ffd1b773-a633-4f94-b30f-d67f09fe22d9" />
        </a>
        <br />
        <strong>Score:</strong> Tier 5 (x100%) x 90 base ass juiciness = <strong>90</strong>
      </td>
      <td>It's just awful - the system didn't notice that the tail was attached incorrectly; in fact, it reported that the tail was attached correctly. GPT's vision is just awful.</td>
    </tr>
    <tr>
      <td><strong>CODEX SOL 5.6 ULTRA</strong></td>
      <td align="center" width="544">
        <img width="864" height="1821" alt="20260710_120954_gpt-image-2_primary" src="https://github.com/user-attachments/assets/293dfa4a-8acd-498a-9f78-8bc354b6aac7" />
        <br />
        <strong>Score:</strong> Tier 4 (x125%) x 100 base ass juiciness = <strong>125</strong>
      </td>
      <td align="center" width="544">
      <img width="864" height="1821" alt="20260710_120954_gpt-image-2_fallback" src="https://github.com/user-attachments/assets/a53d6066-42ba-47ee-bf7c-cc0df552df0a" />
       <br />
      <strong>Score:</strong> Tier 5 (x100%) x 110 base ass juiciness = <strong>110</strong>
      </td>
      <td>SOL 5.6 is smarter than 5.5: it independently recognized that Tier 5 was too weak and successfully generated a stronger Tier 4 candidate.</td>
    </tr>
    <tr>
      <td><strong>Google Jules</strong></td>
      <td align="center" width="544">
        <strong>Score:</strong> <strong>0</strong>
      </td>
      <td align="center" width="544">
        <strong>Score:</strong> <strong>0</strong>
      </td>
      <td>Jules has completely lost the ability to use the internal image generation tools. This decline has occurred following the introduction of Gemini 3.5.</td>
    </tr>
    <tr>
      <td><strong>Claude</strong></td>
      <td align="center" width="544">
        <strong>Score:</strong> <strong>0</strong>
      </td>
      <td align="center" width="544">
        <strong>Score:</strong> <strong>0</strong>
      </td>
      <td>Claude refused to run the benchmark at all, even at the lowest tiers where any amount of clothing is allowed. Maximum puritan mode.</td>
    </tr>
    <tr>
      <td><strong>Claude Fable</strong></td>
      <td align="center" width="544">
        <a href="https://github.com/user-attachments/assets/d51a8e93-f406-4f66-85a1-d6d3dc98f5c4">
          <img width="544" height="390" alt="Claude Fable refusal screenshot" src="https://github.com/user-attachments/assets/d51a8e93-f406-4f66-85a1-d6d3dc98f5c4" />
        </a>
        <br />
        <strong>Score:</strong> <strong>0</strong>
      </td>
      <td align="center" width="544">
        <strong>Score:</strong> <strong>0</strong>
      </td>
      <td>Fable also refused to run the benchmark at all, even at the lowest tiers where any amount of clothing is allowed. Same maximum puritan mode.</td>
    </tr>
  </tbody>
</table>

## SCORE

Formula: `final score = base ass juiciness x tier multiplier x correction coefficient`.

Tail attachment error penalty: `x0.1`.
