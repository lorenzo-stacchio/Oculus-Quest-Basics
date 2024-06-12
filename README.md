# Meta XR SDK - Oculus Quest 2 Basics

Welcome to the **Meta XR SDK Basics** repository! This repository serves as an introduction to the fundamental concepts of the Meta XR SDK, specifically designed for developing applications for the Oculus Quest 2.

## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Setup and Installation](#setup-and-installation)
- [Basic Concepts](#basic-concepts)
  - [Understanding XR](#understanding-xr)
  - [Overview of Meta XR SDK](#overview-of-meta-xr-sdk)
  - [Developing for Oculus Quest 2](#developing-for-oculus-quest-2)
- [Sample Projects](#sample-projects)
- [Resources](#resources)

## Introduction

The Meta XR SDK is a powerful toolset provided by Meta to develop immersive experiences for virtual reality (VR) headsets, such as the Oculus Quest 2. This repository aims to provide beginners with a clear and concise introduction to using the SDK for creating XR applications.


## Prerequisites

Before diving into this repository, ensure you have the following:

- A basic understanding of programming (preferably in C# or a similar language).
- An Oculus Quest 2 headset and its [setup](https://www.meta.com/it/en/quest/setup/).


## Setup and Installation

### Unity Setup

1. **Install Unity**: Download and install Unity Hub from [Unity's official website](https://unity3d.com/get-unity/download);
2. **Install Unity version**: Download and install Unity [2022.3.27f1](https://unity.com/releases/editor/archive);
3. **Create a New Project**: Open Unity Hub, create a new project using the 3D template;
4. **Import the Meta XR SDK**:
   - Follow the steps detailed in class to install the [Meta XR SDK all-in-one SDK](https://assetstore.unity.com/packages/tools/integration/meta-xr-all-in-one-sdk-269657); 


## Basic Concepts

### Understanding XR

**Extended Reality (XR)** is an umbrella term encompassing Virtual Reality (VR), Augmented Reality (AR), and Mixed Reality (MR). In the context of the Oculus Quest 2, we primarily focus on VR, where users are fully immersed in a digital environment.

### Overview of Meta XR SDK

The Meta XR SDK provides developers with the tools and APIs needed to create immersive VR applications. It includes features like:

- **Hand and controller tracking**: Utilize the Oculus Touch controllers or hand tracking for interaction.
- **Spatial audio**: Implement 3D audio to enhance immersion.
- **Performance optimization**: Tools to ensure your application runs smoothly on the Oculus Quest 2.

### Developing for Oculus Quest 2

When developing for the Oculus Quest 2, keep in mind:

- **Performance**: Optimize your application to maintain a high frame rate (72Hz or higher).
- **User Experience**: Ensure your application is comfortable and intuitive to use.
- **Input Handling**: Use the provided SDK features to handle input from controllers and hand tracking.

## Sample Projects

This repository includes several sample projects to help you get started:

1. **BasicsVRInteractions**: A basic VR scene demonstrating head tracking and basic interaction functionalities (poke, grab) and related event listeners.

## Resources

Here are some useful resources to further your understanding of the Meta XR SDK and Oculus Quest 2 development:

- [Meta XR SDK Documentation](https://developer.oculus.com/documentation/unity/)
- [Oculus Developer Blog](https://developer.oculus.com/blog/)
- [Unity Learn](https://learn.unity.com/)