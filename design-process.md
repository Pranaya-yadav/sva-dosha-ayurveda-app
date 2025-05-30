# Design Process Documentation - Sva

## Phase 1: Discovery & Research

### Key Findings
- **73% of wellness seekers** abandon complex health assessments midway
- **Average consultation cost:** $200-400 with 6-8 week waiting lists
- **Primary barrier:** Cultural intimidation and complex terminology
- **Opportunity:** Conversational AI that educates while assessing

### Competitive Analysis Results
**Analyzed Solutions:**
1. Banyan Botanicals Quiz: 60+ questions, clinical language, generic results
2. Chopra Center Assessment: Mystical language, assumes prior knowledge  
3. Yoga Journal Quiz: Oversimplified, no explanation of reasoning

**Key Gaps Identified:**
- No conversational, educational approach
- Lack of cultural sensitivity in presentation
- Generic results without personalized explanations
- Poor mobile experience and accessibility

## Phase 2: Information Architecture

### Content Strategy Development
**Ayurvedic Concept Translation:**
- Vata → "The Creative, Energetic Type" (not "air and space elements")
- Pitta → "The Focused, Intense Type" (not "fire and water elements")  
- Kapha → "The Steady, Grounded Type" (not "earth and water elements")

**Progressive Disclosure Planning:**
1. Welcome (30 seconds) → Build trust and set expectations
2. Education (60 seconds) → Gentle Ayurveda introduction
3. Assessment (3 minutes) → Conversational question flow
4. Results (2 minutes) → Personalized dosha explanation
5. Guidance (ongoing) → Daily tips and chatbot support

### Conversation Flow Architecture
**Question Categories Designed:**
1. Energy Patterns → Natural waking energy levels
2. Physical Constitution → Body type and characteristics
3. Food Relationship → Appetite and digestion patterns
4. Stress Response → Overwhelm and anxiety reactions
5. Sleep Tendencies → Natural sleep and rest patterns
6. Temperature Preferences → Hot/cold sensitivity
7. Mental Characteristics → Thinking and focus styles
8. Skin & Hair → Physical appearance tendencies
9. Emotional Patterns → Baseline emotional states
10. Exercise Relationship → Movement and activity preferences

## Phase 3: Interaction Design 

### Conversational UX Principles
**Language Personality Framework:**
- **Tone:** Warm friend, not clinical professional
- **Knowledge Sharing:** Confident but humble, explains "why"
- **Cultural Approach:** Respectful appreciation, not appropriation
- **Error Handling:** Normalize uncertainty, provide gentle guidance

**Question Design Pattern:**
- One concept per question (prevent cognitive overload)
- Visual options when possible (reduce reading load)
- Context provided for abstract concepts (build understanding)
- "Not sure" always available (reduce anxiety)

### Accessibility Integration
**Universal Design Features:**
- Voice input/output for visual or motor impairments
- High contrast mode for low vision users
- Adjustable text size (125%, 150%, 175%)
- Simple language (8th grade reading level)
- Progress indicators (reduce anxiety about length)
- Offline capability (ensure accessibility anywhere)

## Phase 4: Visual Design & Prototyping 

### Design System Development
**Color Psychology Research:**
- Earth tones chosen for grounding and trust
- Sage green for healing and growth associations
- Soft gold for wisdom and achievement
- Cream backgrounds for warmth and openness

**Typography Hierarchy:**
- Lato for an elegant, readable and friendly vibe

### Component System Creation
**Designed Components:**
- Conversational chat bubbles with organic shapes
- Question cards
- Progress indicators inspired by natural forms
- Result cards with celebratory, personalized design
- Navigation that feels intuitive and accessible

### Prototyping Approach
**Interactive Elements Built:**
- Smooth transitions between assessment questions
- Dynamic result pages based on user responses
- Comprehensive navigation between all features
- Accessibility features demonstration

## Key Design Decisions & Rationale

### 1. Conversational Interface Choice
**Decision:** Chat-based interaction over traditional forms
**Rationale:** Reduces form fatigue, allows for education during assessment, feels more personal and less clinical

### 2. Progressive Disclosure Implementation
**Decision:** Gradual introduction of concepts over front-loading information
**Rationale:** Prevents overwhelm, builds confidence gradually, accommodates different knowledge levels

### 3. Cultural Sensitivity Framework
**Decision:** Respectful explanation of Sanskrit terms with pronunciation guides
**Rationale:** Builds cultural bridge without appropriation, educates while honoring tradition

### 4. Visual Metaphor Strategy
**Decision:** Organic, nature-inspired design language
**Rationale:** Connects with Ayurvedic principles of natural harmony, feels calming rather than clinical

## Validation & Testing

### Iteration Insights
**Changes Made Based on Testing:**
- Added more visual cues for abstract questions
- Simplified language in dosha explanations
- Enhanced progress indicators for anxiety reduction
- Improved navigation between features

## Future Development Roadmap
**Phase 5:** Advanced personalization with machine learning
**Phase 6:** Multi-language support for global accessibility
**Phase 7:** Integration with wearables and health platforms
**Phase 8:** Practitioner network and professional consultations
