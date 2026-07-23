# One-Material — Final Audio Prompts

## Suno AI — Background Music

### Recommended Production Prompt

```text
Create a 15-to-20-second premium cinematic corporate technology stinger for an advanced materials engineering brand. Immediate opening with no long intro. 80 BPM. Restrained orchestral strings, soft piano, clean synth pads, subtle low pulse, modern and hopeful, precise and trustworthy. Build gently from controlled tension to a clean resolved logo ending. No vocals, no choir, no aggressive drums, no trailer booms. Instrumental only. The track must contain a strong, clean 9.8-second section suitable for a premium nuclear-safety engineering advertisement.
```

Select and trim the most stable 9.80-second section.

Output: `OM_BGM_SUNO_v01.wav`

## ElevenLabs — Voice Direction

```text
Language: Korean
Voice: Male, perceived age in the 40s
Tone: Deep, calm, professional, confident, restrained
Delivery: Clear consonants, no theatrical trailer acting, slightly faster than natural speech (approximately 1.05–1.10×), clean sentence endings
```

### Final 9.8-Second Narration

```text
보이지 않는 기술이 원전의 미래를 지킵니다.
One-Material이 원전 안전의 미래를 설계합니다.
```

Timing:

- 00:00.25–00:03.25 — First sentence
- 00:06.10–00:09.45 — Second sentence

Output: `OM_VO_KO_EL_v01.wav`

## Audio Mix

- Narration peak: approximately -6 dBFS
- BGM: 15–18 dB below narration during speech
- BGM fade in: 0.35 s
- BGM fade out: 0.65 s
- Master sample rate: 48 kHz
