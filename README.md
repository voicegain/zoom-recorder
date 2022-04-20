# zoom-recorder
Our Zoom Meeting Recorder does local recording of Zoom meetings (separate recording for each participant) and submits files for transcription to Voicegain

## Install

You can download the Windows .msi installer file from [Releases](https://github.com/voicegain/zoom-recorder/releases)

After install you should see shortcuts in the Start Menu and on the Desktop.

## Configuration

When launched for the first time, the App will automatically go to the Settings view and will stay there until you provide settings that allow it to connect to a Voicegain service - either Cloud or Edge.

The image below shows settings suitable to Voicegain Edge service.
* The first value is a base URL of the Voicegain Edge host
* Second line is a JWT obtained from the Edge Voicegain Web Console. We recommend using a separate context for the Zoom Meeting transcription.
  * See our [helpdesk article about JWT](https://support.voicegain.ai/hc/en-us/articles/360028023691-JWT-Authentication) 
* If it is an Edge install you need to make sure that the Edge checkbox is checked.
* Finally, you can choose to have local recording files be automatically removed after a successfull submit for transcription.

![Zoom Meeting Recorder](ZMR-2.PNG)

When you click Save, the settings will first be tested to see if the necessary Voicegain API requests can be successfully made

# Connecting to a Zoom Meeting 

Once the test passes you will be switched to a page where you enter Zoom Meeting Id and the Password.

![Zoom Meeting Recorder](ZMR-1.PNG)


