![Welcome to the Okaya API](https://www.okaya.me/okaya/wp-content/uploads/2020/05/logo_okaya-copie-1.png "Welcome to the Okaya API")

Welcome to our API.

In our GitHub, you can:
- Access our [QuickStart](https://github.com/SmartTecAPI/api/wiki/New-API-Format "QuickStart") documentation and wiki.
- We have different code examples you can use as well.

Feel free to reach out to us with any question or concern that you have !


<h1>Okaya's Basic Tutorial</h1>

**Before doing this tutorial**, make sure that you have:
1. Created your Okaya <a href='https://www.okaya.me/dashboard/apimanagement/newaccount'>free account</a>.
2. Saved your <em>unique</em> API Key.

<h2>Step 1: Send a check-in to the API</h2>

Make your life simpler and use our <a href='https://github.com/SmartTecAPI/api'>demo code</a> as a starting point. <br>
<ol>
<li>Click the green button <em>Code</em> with the dropdown menu.
<li>Afterwards, select on the option: "Download Zip", which downloads the folder.
<li>Click on the downloaded folder, in which it will bring it to your File Explorer.
<li>Right Click on the api-main.zip folder, and select the option: "Extract All"
<li>Now Click on the api-main folder, then select api-main --> SimpleUploadDemo --> okaya_record_demo.html.
</ol>
Paste your authorization key.<br/>
Record a 20 second video (the camera will automatically stop recording after 20 seconds and submit the video file to the API)<br>

While it is not best practice, we put all the code in a single HTML file to make your life simpler. If you are interested in the inner-workings, check out the code itself using your favorite code editor and you will see how to make call the Checkin end-point.<br>

<h2>Step 2: Reviewing the results</h2>
Once your video is uploaded, the AI takes over and analyzes it. <br>
Because it is in a queue, it may take a few minutes for it to be processed.<br>
Your <a href="https://www.okaya.me/dashboard/apimanagement/apiDashboard">API dashboard</a> will show you the processing status and once the analysis is complete you will be able to see more information about the file.<br>

**Important:** When looking at the analysis result, keep in mind that you are following a basic tutorial. There are other API end-points you can call to get more information about a video that has just been processed.
