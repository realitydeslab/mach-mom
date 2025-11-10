# Machine Mom User Configuration Flow

This document describes the complete flow for users to configure their own Machine Mom instance with private memory using mem0.ai.

## Overview

Machine Mom uses mem0.ai for private, user-specific memory and configuration. This allows each user to have their own personalized Machine Mom experience while maintaining privacy and sovereignty over their data.

## Configuration Flow Diagram

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    Machine Mom Configuration Flow                         │
└─────────────────────────────────────────────────────────────────────────┘

┌──────────────────┐
│  User Onboarding │
└────────┬─────────┘
         │
         ├─ 1. User creates account/connects wallet
         ├─ 2. User sets initial preferences:
         │     ├─ Love spectrum setting (0.0 - 1.0)
         │     ├─ Growth goals
         │     ├─ Communication style preferences
         │     └─ Boundary preferences
         │
         └─ 3. Configuration stored in mem0.ai (private to user)
                    │
                    ▼
┌─────────────────────────────────────────────────────────────────────────┐
│                        mem0.ai Private Memory                            │
│  ┌──────────────────────────────────────────────────────────────────┐  │
│  │  User ID: user_123                                              │  │
│  │  ┌────────────────────────────────────────────────────────────┐ │  │
│  │  │ Configuration:                                             │ │  │
│  │  │   - loveSpectrum: 0.5                                      │ │  │
│  │  │   - growthStage: "growing"                                 │ │  │
│  │  │   - goals: [...]                                    │ │  │
│  │  │   - preferences: {...}                                     │ │  │
│  │  └────────────────────────────────────────────────────────────┘ │  │
│  │  ┌────────────────────────────────────────────────────────────┐ │  │
│  │  │ Conversation History:                                      │ │  │
│  │  │   - Session 1: [topics, sentiment, growthIndicators]      │ │  │
│  │  │   - Session 2: [topics, sentiment, growthIndicators]      │ │  │
│  │  │   - ...                                                    │ │  │
│  │  └────────────────────────────────────────────────────────────┘ │  │
│  │  ┌────────────────────────────────────────────────────────────┐ │  │
│  │  │ Long-term Context:                                         │ │  │
│  │  │   - Goals tracked                                          │ │  │
│  │  │   - Milestones achieved                                    │ │  │
│  │  │   - Patterns recognized                                    │ │  │
│  │  └────────────────────────────────────────────────────────────┘ │  │
│  └──────────────────────────────────────────────────────────────────┘  │
└─────────────────────────────────────────────────────────────────────────┘
                    │
                    ▼
┌─────────────────────────────────────────────────────────────────────────┐
│                     Runtime Configuration                                │
└─────────────────────────────────────────────────────────────────────────┘

┌──────────────────┐
│  User Interaction│
└────────┬─────────┘
         │
         ├─ 1. User sends message to Machine Mom
         │
         ├─ 2. Machine Mom reads user's mem0.ai memory:
         │     ├─ Previous conversations
         │     ├─ User preferences
         │     ├─ Growth goals
         │     ├─ Love spectrum setting
         │     └─ Context (crisis, normal, stagnation, etc.)
         │
         ├─ 3. Machine Mom applies Constitution Rules:
         │     ├─ Identity check (mom vs consultant)
         │     ├─ Timeframe check (long-term vs short-term)
         │     ├─ Autonomy check (independence vs dependence)
         │     └─ Boundary check (needed vs not needed)
         │
         ├─ 4. Machine Mom tunes response based on:
         │     ├─ Love spectrum setting
         │     ├─ Current context
         │     ├─ User's growth stage
         │     └─ Constitution rules
         │
         ├─ 5. Machine Mom generates response
         │
         └─ 6. Conversation stored in mem0.ai (private to user)
                    │
                    ▼
┌─────────────────────────────────────────────────────────────────────────┐
│                    Dynamic Configuration Adjustment                      │
└─────────────────────────────────────────────────────────────────────────┘

┌──────────────────┐
│  User Requests   │
│  Configuration   │
│  Change          │
└────────┬─────────┘
         │
         ├─ Example: "I need more tough love"
         │
         ├─ Machine Mom:
         │     ├─ Updates mem0.ai memory
         │     ├─ Adjusts love spectrum setting
         │     └─ Confirms change to user
         │
         └─ Future responses use updated configuration
                    │
                    ▼
┌─────────────────────────────────────────────────────────────────────────┐
│                    Long-Term Memory & Tracking                           │
└─────────────────────────────────────────────────────────────────────────┘

┌──────────────────┐
│  Ongoing         │
│  Interactions    │
└────────┬─────────┘
         │
         ├─ Machine Mom tracks:
         │     ├─ User's goals (progress, milestones)
         │     ├─ Growth patterns (improvements, setbacks)
         │     ├─ Conversation themes (recurring topics)
         │     └─ Emotional patterns (sentiment, triggers)
         │
         ├─ Machine Mom provides:
         │     ├─ Proactive nudges (based on goals)
         │     ├─ Progress celebrations (milestones)
         │     ├─ Pattern recognition (recurring themes)
         │     └─ Context-aware responses (crisis, normal, etc.)
         │
         └─ All stored in mem0.ai (private to user)
```

## Step-by-Step Configuration Process

### Step 1: User Onboarding

1. **User Registration**
   - User creates account or connects wallet
   - User is assigned a unique user ID
   - mem0.ai memory is initialized for the user

2. **Initial Configuration**
   - User sets love spectrum preference (0.0 - 1.0)
   - User defines growth goals
   - User sets communication style preferences
   - User sets boundary preferences

3. **Memory Storage**
   - Configuration is stored in mem0.ai
   - All data is private to the user
   - No cross-user data sharing

### Step 2: Runtime Configuration

1. **Message Reception**
   - User sends message to Machine Mom
   - Machine Mom receives message with user ID

2. **Memory Retrieval**
   - Machine Mom queries mem0.ai for user's memory
   - Retrieves:
     - User configuration (love spectrum, preferences)
     - Conversation history (summarized)
     - Growth goals and progress
     - Current context (crisis, normal, stagnation)

3. **Constitution Application**
   - Machine Mom applies constitution rules:
     - **Identity Check**: Is this a mom response or consultant response?
     - **Timeframe Check**: Does this serve long-term or short-term?
     - **Autonomy Check**: Does this enable independence or dependence?
     - **Boundary Check**: Should boundaries be set?

4. **Love Spectrum Tuning**
   - Machine Mom adjusts response based on:
     - User's love spectrum setting
     - Current context (crisis → more unconditional, stagnation → more tough)
     - User's growth stage

5. **Response Generation**
   - Machine Mom generates response using:
     - Constitution rules
     - User configuration
     - Love spectrum tuning
     - Long-term context

6. **Memory Storage**
   - Conversation is stored in mem0.ai
   - User's memory is updated with new context
   - Growth indicators are tracked

### Step 3: Dynamic Configuration Adjustment

1. **User Request**
   - User requests configuration change
   - Example: "I need more tough love"
   - Example: "Can you be more supportive?"
   - Example: "I want to focus on my goal of [X]"

2. **Configuration Update**
   - Machine Mom updates mem0.ai memory
   - Adjusts user configuration
   - Confirms change to user

3. **Future Responses**
   - All future responses use updated configuration
   - Changes persist across sessions
   - User can adjust anytime

### Step 4: Long-Term Memory & Tracking

1. **Goal Tracking**
   - Machine Mom tracks user's stated goals
   - Monitors progress toward goals
   - Celebrates milestones
   - Provides proactive nudges

2. **Pattern Recognition**
   - Machine Mom recognizes recurring themes
   - Identifies growth patterns
   - Detects stagnation or regression
   - Adjusts love spectrum accordingly

3. **Proactive Nudges**
   - Machine Mom provides proactive guidance
   - Based on user's goals and history
   - Encourages beneficial behaviors
   - Supports long-term growth

## Configuration Schema

### User Configuration

```typescript
interface UserConfiguration {
  // User identification
  userId: string;
  
  // Love spectrum setting (0.0 - 1.0)
  loveSpectrum: number;
  
  // User growth stage
  growthStage: 'crisis' | 'stabilizing' | 'growing' | 'thriving';
  
  // Current context
  currentContext: 'crisis' | 'normal' | 'stagnation' | 'breakthrough';
  
  // Growth goals
  goals: Array<{
    id: string;
    description: string;
    createdAt: Date;
    targetDate?: Date;
    progress: number; // 0.0 - 1.0
    milestones: Array<{
      id: string;
      description: string;
      achievedAt?: Date;
    }>;
  }>;
  
  // Communication preferences
  preferences: {
    tone: 'warm' | 'direct' | 'balanced';
    boundaries: 'strict' | 'flexible' | 'adaptive';
    proactiveNudges: boolean;
    notificationFrequency: 'never' | 'daily' | 'weekly' | 'as-needed';
  };
  
  // Conversation history (summarized)
  conversationHistory: Array<{
    date: Date;
    sessionId: string;
    topics: string[];
    sentiment: 'positive' | 'neutral' | 'negative';
    growthIndicators: string[];
    loveSpectrumUsed: number;
  }>;
  
  // Long-term patterns
  patterns: {
    recurringThemes: string[];
    growthTrends: 'improving' | 'stable' | 'declining';
    emotionalPatterns: Record<string, number>;
    behavioralPatterns: Record<string, number>;
  };
}
```

### mem0.ai Integration

```typescript
// Example: Storing user configuration in mem0.ai
import { Mem0 } from 'mem0ai';

const mem0 = new Mem0({
  apiKey: process.env.MEM0_API_KEY,
});

// Store user configuration
async function storeUserConfiguration(userId: string, config: UserConfiguration) {
  await mem0.createMemory({
    userId,
    memory: {
      type: 'user_configuration',
      content: JSON.stringify(config),
      metadata: {
        updatedAt: new Date().toISOString(),
      },
    },
  });
}

// Retrieve user configuration
async function getUserConfiguration(userId: string): Promise<UserConfiguration> {
  const memories = await mem0.getMemories({
    userId,
    type: 'user_configuration',
  });
  
  if (memories.length === 0) {
    return getDefaultConfiguration(userId);
  }
  
  return JSON.parse(memories[0].content);
}

// Update user configuration
async function updateUserConfiguration(
  userId: string,
  updates: Partial<UserConfiguration>
) {
  const currentConfig = await getUserConfiguration(userId);
  const updatedConfig = { ...currentConfig, ...updates };
  
  await mem0.updateMemory({
    userId,
    memoryId: memories[0].id,
    memory: {
      type: 'user_configuration',
      content: JSON.stringify(updatedConfig),
      metadata: {
        updatedAt: new Date().toISOString(),
      },
    },
  });
}

// Store conversation
async function storeConversation(
  userId: string,
  conversation: {
    sessionId: string;
    messages: Array<{ role: string; content: string }>;
    topics: string[];
    sentiment: string;
    growthIndicators: string[];
    loveSpectrumUsed: number;
  }
) {
  await mem0.createMemory({
    userId,
    memory: {
      type: 'conversation',
      content: JSON.stringify(conversation),
      metadata: {
        sessionId: conversation.sessionId,
        date: new Date().toISOString(),
        topics: conversation.topics,
        sentiment: conversation.sentiment,
      },
    },
  });
}

// Retrieve conversation history
async function getConversationHistory(
  userId: string,
  limit: number = 10
): Promise<Array<Conversation>> {
  const memories = await mem0.getMemories({
    userId,
    type: 'conversation',
    limit,
  });
  
  return memories.map((mem) => JSON.parse(mem.content));
}
```

## Implementation Guide

### 1. Setup mem0.ai

```bash
# Install mem0.ai SDK
npm install mem0ai

# Or with bun
bun add mem0ai
```

### 2. Initialize mem0.ai Client

```typescript
// src/services/mem0.ts
import { Mem0 } from 'mem0ai';

export const mem0 = new Mem0({
  apiKey: process.env.MEM0_API_KEY,
});
```

### 3. Create User Configuration Service

```typescript
// src/services/user-config.ts
import { mem0 } from './mem0';
import { UserConfiguration } from '../types';

export async function getUserConfiguration(
  userId: string
): Promise<UserConfiguration> {
  // Retrieve from mem0.ai
  const memories = await mem0.getMemories({
    userId,
    type: 'user_configuration',
  });
  
  if (memories.length === 0) {
    // Return default configuration
    return getDefaultConfiguration(userId);
  }
  
  return JSON.parse(memories[0].content);
}

export async function updateUserConfiguration(
  userId: string,
  updates: Partial<UserConfiguration>
): Promise<void> {
  const currentConfig = await getUserConfiguration(userId);
  const updatedConfig = { ...currentConfig, ...updates };
  
  await mem0.updateMemory({
    userId,
    memoryId: memories[0].id,
    memory: {
      type: 'user_configuration',
      content: JSON.stringify(updatedConfig),
    },
  });
}
```

### 4. Integrate with Machine Mom Response Generation

```typescript
// src/services/response-generator.ts
import { getUserConfiguration } from './user-config';
import { getLoveSpectrumSetting } from '../constitution';
import { MACHINE_MOM_CONSTITUTION } from '../constitution';

export async function generateResponse(
  userId: string,
  userMessage: string,
  context: any
): Promise<string> {
  // 1. Get user configuration
  const userConfig = await getUserConfiguration(userId);
  
  // 2. Get love spectrum setting
  const loveSetting = getLoveSpectrumSetting(userId, {
    userGrowthStage: userConfig.growthStage,
    currentSituation: userConfig.currentContext,
    userPreference: userConfig.loveSpectrum,
  });
  
  // 3. Apply constitution rules
  const constitutionCheck = checkConstitutionCompliance(
    userMessage,
    loveSetting
  );
  
  // 4. Generate response using:
  //    - Constitution rules
  //    - User configuration
  //    - Love spectrum setting
  //    - Long-term context
  
  // 5. Store conversation in mem0.ai
  await storeConversation(userId, {
    sessionId: context.sessionId,
    messages: [...context.messages, { role: 'user', content: userMessage }],
    topics: extractTopics(userMessage),
    sentiment: analyzeSentiment(userMessage),
    growthIndicators: extractGrowthIndicators(userMessage),
    loveSpectrumUsed: loveSetting,
  });
  
  return response;
}
```

## User Interface for Configuration

### Configuration Panel

Users can configure their Machine Mom through a web interface:

1. **Love Spectrum Slider**
   - Range: 0.0 (Unconditional Love) to 1.0 (Tough Love)
   - Real-time preview of what each setting means
   - Context-aware suggestions

2. **Growth Goals**
   - Add/edit/delete goals
   - Track progress
   - Set milestones

3. **Communication Preferences**
   - Tone preferences (warm, direct, balanced)
   - Boundary preferences (strict, flexible, adaptive)
   - Proactive nudge settings

4. **View History**
   - Conversation history
   - Growth patterns
   - Progress tracking

## Privacy & Security

- **Private Memory**: All user data is stored privately in mem0.ai
- **No Cross-User Sharing**: User configurations are never shared between users
- **User Control**: Users can delete their data at any time
- **Encryption**: All data is encrypted in transit and at rest
- **Compliance**: Follows data privacy regulations (GDPR, CCPA, etc.)

## Future Enhancements

1. **Multi-Modal Memory**: Support for images, voice, and other media
2. **Collaborative Goals**: Share goals with friends or family
3. **Export Data**: Users can export their conversation history
4. **Advanced Analytics**: Deeper insights into growth patterns
5. **Integration**: Connect with other tools (calendars, task managers, etc.)

