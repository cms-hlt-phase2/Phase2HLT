## Phase 2 HLT code and configuration

This reporitory will eventually contain the specific code and configurations for the Phase 2 HLT studies, while they are staged for integration in the official CMSSW release.

The expected workflow is something like
```bash
cmsrel CMSSW_11_0_0_pre3
cd CMSSW_11_0_0_pre3/src
cmsenv
git clone git@github.com:cms-hlt-phase2/Phase2HLT.git
scram b -j
```
