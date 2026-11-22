# GAME_PROGRAM-EXP-6

## Implementing AI Character Movement Using Behaviour Trees in Unreal Engine

### Aim
To create an AI character in Unreal Engine and implement intelligent movement and behaviour using AI Controllers, Blueprint Visual Scripting, and Behaviour Trees.

### Experiment Description
This experiment demonstrates how to create an AI-controlled character in Unreal Engine and implement autonomous movement using Behaviour Trees. The AI character is configured using an AI Controller and Blueprint Event Graph to execute movement behaviour based on the defined logic in the Behaviour Tree.

### Software Requirements
- Unreal Engine 5
- Unreal Engine Blueprint Visual Scripting
- Unreal Engine AI Behaviour Tree System

### Implementation

**1. Creating the AI Character**
- Create a new Blueprint Class and select Character as the parent class.
- Name the Blueprint `MyAICharacter`.
- Configure the character mesh and movement components.
- Set the AI Controller Class to an appropriate AI Controller.
- Configure Auto Possess AI to `Placed in World or Spawned`.

**2. Implementing the AI Character Event Graph**
- Open the `MyAICharacter` Blueprint.
- Implement the required Event Graph logic.
- Configure the AI character to communicate with its AI Controller.
- Use movement-related nodes to control the character's behaviour.
- Compile and save the Blueprint.

**3. Creating the Behaviour Tree**
- Create a new Behaviour Tree asset.
- Assign an appropriate Blackboard asset.
- Open the Behaviour Tree Editor.
- Add the required root, composite, and task nodes.
- Configure the execution flow to define the AI character's behaviour.

**4. Configuring AI Behaviour**
- Connect the Behaviour Tree to the AI Controller.
- Configure the necessary Blackboard values.
- Define the movement behaviour through the Behaviour Tree.
- Ensure the AI character can execute the configured behaviour during gameplay.

**5. Testing the AI Character**
- Place the AI character in the game environment.
- Ensure that the navigation mesh covers the walkable area.
- Run the game and observe the AI character.
- Verify that the AI character executes the configured behaviour.

### Screenshots

**1. AI Character Blueprint**

![AI Character](https://github.com/user-attachments/assets/31f11a56-41ad-41a2-9377-5fdc96f0aa17)

**2. AI Character – Event Graph**

![AI Character Event Graph](https://github.com/user-attachments/assets/60a9aef7-e288-4b02-9561-a792a3e3038c)

**3. Behaviour Tree**

![Behaviour Tree](https://github.com/user-attachments/assets/ddd0f9ca-889d-4bb7-bb9d-7badd46ba700)

### Result
Successfully created an AI character in Unreal Engine and implemented AI behaviour using Blueprint Visual Scripting, AI Controllers, and Behaviour Trees to control autonomous character movement.
