Overview
TechSee provides an iOS Mobile SDK for iOS integration. The TechSee iOS SDK is designed to embed the TechSee Visual Assistance application within a customer's mobile application. The SDK offers comprehensive functionality for joining a TechSee session from the hosting app. The purpose of this document is to furnish a technical overview of the API along with code examples.
SDK Features 
The TechSee Mobile SDK enables the integration of the TechSee Visual Assistance application, allowing an agent to assist a customer remotely. The TechSee Mobile SDK supports the following features:
Screen Mirroring of the iOS device (of the customer ) 
An agent can exchange images with the Client 
Text Chat support through the SDK
Supported modes: 
Native: Screen mirroring, Application mirroring, Video application
Web view: Photo mode, Video
Switch between modes (Partial- not all modes are supported)
Live assist flow (Agent mode). Supported in web view
Pause/Resume session. From the customer and agent side
End the session. From the customer and agent side
Branding
According to the branding requirements create an invitation link
Multi-language support (Limited )
Location detection (only iOS)
Application mode pointer



Supported Sessions
The mobile SDK provides built-in support for multiple session types, including:
Application Mirroring: Only the hosting application screen is shared with the agent dashboard.
Screen Mirroring: The entire mobile screen is shared with the agent dashboard.
Video Mode: The mobile camera is shared with the agent dashboard.
Photo Mode: The customer can take pictures with their mobile camera and upload them to the agent dashboard.
Image Upload: A mode where the native camera application is used to take images and upload them to the agent dashboard.
Video Application Mode: The mobile camera is shared with the agent dashboard.
Moreover, if configured to support it, the agent can seamlessly switch the customer from one mode to another, and the SDK will handle it seamlessly. Note that for displaying video, photo, and image upload modes, the application internally uses a WebView to present these pages. The initial session type selection is made by the agent when initiating the session, and switching between session types is also managed through the agent’s dashboard. The integration guide below covers all these modes and transitions.
Supported Languages 
English, French, Spanish, Turkish, Italian, German, Portuguese, Japanese,
Korean, Greek, Dutch, Polish, Russian, Slovak, Swedish, Thai, Hungarian, Albanian, Bulgarian, Czech, Danish, Croatian, Romanian, Slovenian, Canadian French







Requirements/Prerequisites 
IOS 13 or higher Version 
Compatible with Swift or Objective C
