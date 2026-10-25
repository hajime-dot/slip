# Slip

Teacher-run classroom quiz rooms (multiple-choice and true/false) with QR codes and live tally.

**Live demo:** https://blaze-raven-iris-cactus.grok.me/

## Pages

- [index.html](index.html) — Teacher: open a room, add MC / True-False questions in order
- [enter.html](enter.html) — Student: enter a room code to join

## Notes

These are page shells from the Grok-hosted app. Interactive features (room creation, QR, live tally, answers) depend on the original host's JavaScript and backend.

For classroom use, open the live demo. The files here are a snapshot / reference.

## How it works

- Teacher builds a sequence of MC and True/False questions, then opens a room.
- Students join only via QR code or room code — they cannot open rooms or see the tally.
- One shared database; each room's private tally link is separate.
