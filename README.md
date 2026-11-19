# LeRobot Force Insertion

Imitation learning for bimanual manipulation in MuJoCo with [LeRobot](https://github.com/huggingface/lerobot):
ACT policies on the ALOHA simulation, a few-shot data-efficiency study, and a comparison of
vision-only vs. vision + wrist force/torque input for contact-rich insertion.

> 🚧 Work in progress.

## Plan

- [ ] Baseline: ACT on `AlohaTransferCube-v0`, success rate over 50 evaluation episodes
- [ ] Few-shot study: ACT on `AlohaInsertion-v0` with 10 / 25 / 50 demonstrations
- [ ] Wrist force/torque sensors in the MJCF model, scripted demos recorded with F/T
- [ ] Vision-only vs. vision + F/T comparison and failure analysis
