# Buy list
- [x] Tiny black screws
- [x] Reciprocating (sagital) saw
- [x] Longer blade for the oscillating saw

  Orthomed contacted 18/09/24 and should hear back by 27/09/24 latest. They are contacting their suppliers to see if they can make 60 to 80mm long blades. There might be a minimum order, etc.

# Questions
- [x] Angle of tibial tunnel. Should it be pre-decided?

  65 to 75 seems to be standard [1](https://journals.sagepub.com/doi/abs/10.1177/03635465010290050801), [2](https://www.sciencedirect.com/science/article/abs/pii/0749806395900039), [3](https://link.springer.com/article/10.1007/s00264-014-2457-0).
Comfortable leaving it open to surgeon's decision and recording/reporting it.
- [x] Femoral interference screw must be external. How is that achieved? second hole to go through soft tissue?
  No second hole. Use the same incision that allows the ligament to come through the muscles of the femur.
- [x] Tension to the ligament. 20-30N? Opted for graft attached at 20N, 20 degrees on the tibial tunnel.
  Not measured. Just following surgeon standard practice

# Problems
- [ ] Knee dislocated and partial pull of the LARS through the tibial tunnel from distraction.
- [ ] Before removing knee from robot, zero the forces then remove screws. Failed to do this, ACL avulsed.
- [x] Rigidity of LVDT rig. Does moisture damage the epoxy?
  Do a test with wrapping the implant + epoxy in a wet towel. Issue may have been that it hadn't cured long enough.
- [x] Location of posterior hole on shell. Probably should be 10mm distance between second and third holes.
- [x] LVDT sync with robot data
  Added all LVDTs as sensors within simvitro. Requires double-checking when restarting the project.
- [x] Matrices saved per trajectory run. Code acquired from Sander.
