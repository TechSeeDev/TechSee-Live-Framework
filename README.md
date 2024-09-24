
<h1>Overview</h1>
<p>TechSee provides an iOS Mobile SDK for iOS integration. The TechSee iOS SDK is designed to embed the TechSee Visual Assistance application within a customer&apos;s mobile application. The SDK offers comprehensive functionality for joining a TechSee session from the hosting app. The purpose of this document is to furnish a technical overview of the API along with code examples.</p>
<h2>SDK Features&nbsp;</h2>
<p>The TechSee Mobile SDK enables the integration of the TechSee Visual Assistance application, allowing an agent to assist a customer remotely. The TechSee Mobile SDK supports the following features:</p>
<p>Screen Mirroring of the iOS device (of the customer )&nbsp;</p>
<p>An agent can exchange images with the Client&nbsp;</p>
<p>Text Chat support through the SDK</p>
<h3>Supported modes:&nbsp;</h3>
<p>Native: Screen mirroring, Application mirroring, Video application</p>
<p>Web view: Photo mode, Video</p>
<p>Switch between modes (Partial- not all modes are supported)</p>
<p>Live assist flow (Agent mode). Supported in web view</p>
<p>Pause/Resume session. From the customer and agent side</p>
<p>End the session. From the customer and agent side</p>
<h3>Branding</h3>
<p>According to the branding requirements create an invitation link</p>
<p>Multi-language support (Limited )</p>
<p>Location detection (only iOS)</p>
<p>Application mode pointer</p>
<p><br></p>
<h3>Supported Sessions</h3>
<p>The mobile SDK provides built-in support for multiple session types, including:</p>
<p>Application Mirroring: Only the hosting application screen is shared with the agent dashboard.</p>
<p>Screen Mirroring: The entire mobile screen is shared with the agent dashboard.</p>
<p>Video Mode: The mobile camera is shared with the agent dashboard.</p>
<p>Photo Mode: The customer can take pictures with their mobile camera and upload them to the agent dashboard.</p>
<p>Image Upload: A mode where the native camera application is used to take images and upload them to the agent dashboard.</p>
<p>Video Application Mode: The mobile camera is shared with the agent dashboard.</p>
<p>Moreover, if configured to support it, the agent can seamlessly switch the customer from one mode to another, and the SDK will handle it seamlessly. Note that for displaying video, photo, and image upload modes, the application internally uses a WebView to present these pages. The initial session type selection is made by the agent when initiating the session, and switching between session types is also managed through the agent&rsquo;s dashboard. The integration guide below covers all these modes and transitions.</p>
<h3>Supported Languages&nbsp;</h3>
<p>English, French, Spanish, Turkish, Italian, German, Portuguese, Japanese,</p>
<p>Korean, Greek, Dutch, Polish, Russian, Slovak, Swedish, Thai, Hungarian, Albanian, Bulgarian, Czech, Danish, Croatian, Romanian, Slovenian, Canadian French</p>
<p><br></p>
<h2>Requirements/Prerequisites&nbsp;</h2>
<p>IOS 13 or higher Version&nbsp;</p>
<p>Compatible with Swift or Objective C</p>
