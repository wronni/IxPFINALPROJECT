# Confirm - Interactive Stress Relief Prototype

A low-fidelity interactive prototype demonstrating calm, user-centered interaction design for emotional wellbeing.

## Purpose

Confirm helps users pause, breathe, and emotionally reset when feeling overwhelmed. The design prioritizes emotional safety, user control, and gentle reassurance over productivity metrics or urgency.

## Core Interaction Principles

1. **User Control** - Users always have control over their experience
2. **No Irreversible Actions** - Every step can be undone or stopped
3. **Clear Reassurance** - Each interaction previews what comes next
4. **Exit Anytime** - Users can leave at any point without judgment

## Interaction Flow

### 1. Welcome Screen
- **Affordance**: Acknowledges the user's emotional state without pressure
- **Language**: "You deserve a moment" - affirming, not demanding
- **Actions**: Two clear choices with equal visual weight
  - Primary: "I need a moment"
  - Secondary: "Maybe later"

### 2. Preview/Confirmation Screen
- **Affordance**: Shows exactly what will happen next
- **Purpose**: Reduces anxiety by removing uncertainty
- **Content**:
  - Step-by-step preview of the breathing exercise
  - Reassurance of user control
  - Clear exit path ("Go back")

### 3. Breathing Exercise Screen
- **Affordance**: Visual breathing guide (expanding/contracting circle)
- **Interaction**:
  - 5 breathing cycles (12 seconds each)
  - 4s inhale → 2s hold → 4s exhale → 2s rest
  - Visual and text cues synchronized
  - Progress indicator (non-judgmental)
- **Control**: "Stop" button always visible

### 4. Completion Screen
- **Affordance**: Gentle affirmation of the action taken
- **Language**: "You took a moment" - acknowledges without judgment
- **Actions**:
  - Repeat the exercise
  - Return to regular activities

### 5. Early Exit Screen
- **Affordance**: Validates the choice to stop
- **Language**: "That's okay" - non-judgmental
- **Actions**: Option to return or confirm exit

## Design Language

### Visual Tone
- **Colors**: Soft gradients (lavender to purple)
- **Shapes**: Rounded corners (32px radius on cards, 50% on circles)
- **Spacing**: Generous whitespace for breathing room
- **Shadows**: Subtle, soft shadows (no harsh edges)

### Typography
- **Hierarchy**: Clear size distinction without being aggressive
- **Weight**: Medium weights for balance
- **Color**: Muted grays and blues for calm

### Motion
- **Transitions**: Slow, gentle (600ms for screens, 4s for breathing)
- **Easing**: Ease-in-out for natural feel
- **Purpose**: Every animation supports the emotional goal

## Affordances

### Button Design
- **Primary Action**: Gradient background, clear call-to-action
- **Secondary Action**: Neutral background, equal respect
- **Exit/Stop**: Always visible, never hidden
- **Hover States**: Subtle lift, no jarring changes

### Visual Feedback
- **Breathing Circle**: Scales smoothly to guide breath
- **Text Cues**: Change in sync with visual animation
- **Progress Counter**: Informative, not pressuring

## Technical Implementation

### Structure
- Single-page HTML prototype
- Vanilla JavaScript (no dependencies)
- CSS transitions and animations
- Responsive design (mobile-friendly)

### States
- 5 distinct screens with smooth transitions
- State management via screen visibility
- Cleanup on exit to prevent memory leaks

### Timing
- **Screen transitions**: 600ms fade + slide
- **Breathing cycle**: 12s total (4s in, 2s hold, 4s out, 2s rest)
- **Total exercise**: ~60 seconds (5 cycles)

## Usage

### Running the Prototype
1. Open `index.html` in a modern web browser
2. Interact with the prototype using your mouse or touch screen
3. Experience the full flow or exit at any time

### Testing Focus Areas
- **Emotional Response**: Does the language feel supportive?
- **Clarity**: Is it clear what each button will do?
- **Control**: Does the user feel in control throughout?
- **Safety**: Can the user exit without guilt or friction?

## Interaction Design Considerations

### Affordance Analysis
- **Buttons**: Rounded shapes suggest softness, gradients suggest depth
- **Circle**: Expanding/contracting suggests breathing motion
- **Exit button**: Positioned consistently (top-right) for predictability

### Signifiers
- **Text labels**: Clear, imperative voice ("I need a moment")
- **Icons**: Minimal use (checkmark for completion)
- **Visual weight**: Guides attention without demanding it

### Feedback
- **Immediate**: Hover states, button presses
- **Progressive**: Cycle counter, breathing phases
- **Confirmatory**: Completion screen, exit screen

### Conceptual Model
- **Mental model**: A safe space to pause, not a timer or task
- **Metaphor**: Breathing guide as a companion, not instructor
- **Mapping**: Natural correspondence between circle size and breath

## Design Decisions

### Why No Timer Display?
- Timers create pressure and defeat the calming purpose
- Cycle counter provides progress without urgency

### Why Preview Screen?
- Reduces anxiety by removing unknowns
- Respects user agency by explaining before doing
- Builds trust through transparency

### Why Equal Button Weight?
- "Maybe later" isn't a failure - it's respected equally
- No dark patterns or shame-based design
- True user agency, not manipulated consent

### Why Soft Gradients?
- Creates visual interest without stimulation
- Suggests depth and dimensionality
- Aligns with calming color psychology

## Educational Context

This prototype demonstrates:
- **Affordances**: Visual properties that suggest how to interact
- **Signifiers**: Indicators of where action should take place
- **Feedback**: Communicating the results of actions
- **Conceptual Models**: User's understanding of how the system works
- **Emotional Design**: How design choices affect user feelings

## Future Considerations

Potential enhancements (not in scope for lo-fi prototype):
- Multiple breathing patterns
- Customizable cycle length
- Gentle sounds or haptics
- Personal affirmation library
- Dark mode for evening use

---

**Design Philosophy**: Every pixel serves the user's emotional wellbeing. Every interaction respects their autonomy. Every word acknowledges their humanity.
