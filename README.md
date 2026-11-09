# Phloem Protocol

Recursive attribution rewards for AI architecture research, settled in SAP on DSM.

**Status:** open design draft for comment. No implementation exists yet.

Paper: [Phloem-Protocol-2026-11.pdf](Phloem-Protocol-2026-11.pdf)

## Feedback
Counterexamples to anything in Section 10 (open problems) are the most useful thing you can send.
Open an issue, or contact hello@pinealab.com or @pepedzekichen on X, Telegram or Discord.

## Verify
SHA-256: `fa212d6f8d5023fc7d426bbcd0042a9f8df5b9c118ef37e1998eb2e378d59e68`

Timestamp (OpenTimestamps): `ots verify Phloem-Protocol-2026-11.pdf.ots`

Signature (SSH ed25519):
    echo "pepedzekichen $(cat phloem_key.pub)" > allowed_signers
    ssh-keygen -Y verify -f allowed_signers -I pepedzekichen -n file -s Phloem-Protocol-2026-11.pdf.sig < Phloem-Protocol-2026-11.pdf

## License
CC BY 4.0
