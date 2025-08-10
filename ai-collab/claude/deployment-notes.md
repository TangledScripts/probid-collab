# Claude Deployment Notes

## 🚀 Infrastructure Status: OPERATIONAL

### VPS Environment
- **Server:** srv920579.hstgr.cloud
- **Location:** /opt/probid-dev/
- **Port Management:** Adapting to existing infrastructure (port 3001 currently allocated)
- **Security:** UFW firewall, SSH key authentication, fail2ban protection

### Current Deployment Challenge
- Port 3001 is occupied by existing infrastructure
- Need to adapt ProBid to available ports rather than force port reallocation
- Mobile app must be flexible with port assignment

### Next Actions Required
1. ✅ Created public collaboration repo (TangledScripts/probid-collab)
2. ⏳ Make probid-beta private for code security
3. ⏳ Configure mobile app for flexible port assignment
4. ⏳ Deploy mobile app on available port
5. ⏳ Test mobile functionality and provide URL to Tony

### Mobile App Requirements
- Must work with dynamic port assignment
- Touch-optimized interface for construction site use
- Real-time camera and AI detection capabilities
- Consent management for site owner approval
- Voice input/output functionality

### Patch Workflow Ready
- Private repo: TangledScripts/probid-beta (protected code)
- Public collab: TangledScripts/probid-collab (coordination only)
- Patch application: Ready for ChatGPT iteration files

## Current Status
Infrastructure complete, awaiting port resolution and mobile deployment.