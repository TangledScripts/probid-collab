# ProBid Master Context & Working Plan

## 🎯 Project Mission
AI-powered mobile construction bidding assistant that helps contractors create professional bids directly from job sites using their phones.

## 🏗️ Current Infrastructure Status: ✅ COMPLETE

### Live Development Environment
- **Mobile Testing URL:** http://srv920579.hstgr.cloud:3001
- **VPS Environment:** `/opt/probid-dev/` 
- **Docker Integration:** Containerized deployment ready
- **Google Cloud:** probid-dev project with Vision, Speech, Storage APIs
- **Development Workflow:** Real-time build-test-deploy cycle

### Technical Foundation Ready
- **Backend:** Node.js/Express server operational
- **Database:** Google Firestore configured  
- **APIs:** Vision API (photo analysis), Speech API (voice input), Storage (media)
- **Mobile Optimization:** PWA-ready, touch-optimized interface
- **Security:** VPS hardening, UFW firewall, SSH key auth

## 🤖 AI Collaboration Model

### Role Distribution
**ChatGPT (Feature Lead):**
- User interface design and implementation
- Feature workflows and user journeys  
- Business logic and bid generation algorithms
- Mobile PWA optimization
- User testing and feedback integration

**Claude Code (Infrastructure & APIs):**
- Google Cloud service integration
- Backend API development and database operations
- VPS deployment pipeline management
- Security and authentication infrastructure
- Real-time mobile testing coordination

### Development Philosophy
- **Mobile-First:** Every feature tested immediately on phones
- **Incremental:** Build piece-by-piece, avoid over-architecture  
- **Real-world focus:** Actual construction site usability
- **AI-powered:** Leverage Google Cloud AI for intelligent features

## 📱 Core Features Roadmap

### Phase 1: Site Walk MVP ✅ DEPLOYED
- Mobile camera interface with consent management
- Real-time AI object detection (outlets, fixtures, doors, windows)
- Voice input and audio feedback
- Photo capture with gallery
- Recording timer and controls

### Phase 2: Enhanced Analysis (Next)
- Measurement tools and AR overlays
- Discrepancy detection vs blueprints  
- Voice transcription and notes
- Multi-room navigation

### Phase 3: Bid Generation
- Cost estimation algorithms
- Professional bid document creation
- Client communication features
- Project management integration

## 🔄 Patch-Based Development Workflow

### For ChatGPT Patches:
```bash
# Apply iteration patch to private repo
git checkout -b probid/iteration-X
curl -L -o /tmp/iteration-X.patch [URL or paste from chat]
git apply --3way /tmp/iteration-X.patch  
git add -A && git commit -m "ProBid: Iteration X — [description]"
git push -u origin probid/iteration-X
```

### For Code Updates:
- **Private Repo:** TangledScripts/probid-beta (all proprietary code)
- **Public Collab:** TangledScripts/probid-collab (docs, patches, coordination)
- **Security:** No sensitive code or credentials in public repo

## 🚀 Current Status
**Infrastructure:** Complete and operational  
**Mobile Testing:** Live and accessible  
**Next Step:** Feature development patches from ChatGPT  
**Deployment:** Real-time mobile validation ready

Ready for collaborative feature development!