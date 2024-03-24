# Review: Use VS Code

VS code is an open source code editor that includes developer tooling. It is similar to Jupyter Notebooks and Colab, but it includes more features. VS code provides built-in support with [Intellisense](https://code.visualstudio.com/docs/editor/intellisense#:~:text=IntelliSense%20is%20a%20general%20term,%2C%20and%20%22code%20hinting.%22) code completion, an interactive debugger, and other build and scripting tools. VS code has a simple design that is easy to use. Its intuitive features make it a great choice for coding in Python!

## **Using VS Code with Python**

To use VS code for Python, you will need to have Python3, VS Code, and the VS Code Python extension installed. Make sure that you have Python3 installed on your computer by typing the following command in the terminal on your computer. 

Linux/macOS: open a Terminal Window and type the following command:

`python3 --version `

Windows: open a command prompt and run the following command:

`py -3 –version`

If Python3 is installed the output should look like this:

`$python3 -- version`

`Python 3.11.3`

If it is not installed the output will look like this:

`$python3 -- version`

command not found: python

## **Download VS Code and install the Python extension**

You can download VS code [here](https://code.visualstudio.com/Download). You can use VS code on Windows, Mac, and Linux operating systems. Download the version that is compatible with your operating system. Follow the download prompts. Once the download and installation is complete you will be able to open VS Code and begin using it. 

Next, you will install the Python extension. You can do this by visiting the [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=ms-python.python). Follow the download instructions there.  You can check to make sure the Python extension was added successfully by clicking on this icon in VS Code.

![Image of the Python extension from VS Code Marketplace](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/-FVGgVsDSq-gRgJom_N7MA_ca78965413c94939b85ee2fbe2c7fbf1_1QwSA3X4xFNF9WENXcRH0eEysjQJneVKTGOSvfey3ckcTtl7AP96TEaiqWN-D6n3cU3OUcOEQHUR7fr0VQp--NN5I7792_TDrhIuavpap8F4PxPUaMFUNJDtE-hb3BbC9DTbM1E-HfUAWoqqVOmMBlUzxfPeArHHTIpEahcbClKCY9M28SM7h1J6y-AHjzo?expiry=1705536000000&hmac=OFMTksxjpdFbRn-j3fWnh1k7s2uQZObmmm3i1YD5SEI)

**Note:** You cannot use  VS Code Marketplace to install the Python extension on MacOS. 

For MacOS, open the command palette in VS code. You can do this by hitting Cmd+Shift+P. Type ‘**shell command**’. Find the Shell Command: **Install ‘code’ command in PATH**. 

Once this is completed you can begin writing, running, and debugging Python code in VS Code!

**Pro tip:** To try VS Code without downloading or installation click [here](https://vscode.dev/).

## **Create a Python File**

To create a Python file in VS Code go to File → New File… → Python File. A new workspace will appear, and you can begin writing your Python code. Let’s test it out with a simple statement. Type the following statement into the new workspace.

print(“Hello World!”)

Next, click on  the Run and Debug icon in the left hand toolbar. 

![Image of how to run and debug a code snippet: print("Hello World!") in VS  Code](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/cyHGbSISTC6w2RemkLO8Yw_723ba15cbb6444b4a3e0cfd7febee6f1_iymu6bz-Prp2xdZfzPyDr5b7ccgSd5kEW4i1LchqCnA7H4gjqjpOoJgRJKtJonZ_7J5mRpziTOHJWzNwYfhjg815PKNlsetjUZPWinn048_VVYiyVC6Xzr1hkN7p4eTevSZNcCCJUzJ5POzVe5Xng6BDvkioYj3eD5blMDt7RBLZQRDoeNnNkxsRlRxf4mk?expiry=1705536000000&hmac=J273OLyx84AUkI1iZmwQfiWgm94P8TN_-5SOAPZ57zY)

Then, click Run and Debug here:

![Image of the Run and Debug button in VS Code](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/yuPwhbBlRnqR4_fvE3J4VA_387a5375ea574a9293d451c11a1512f1_mHX4ORsZwIf7XWQ8YykyTEjRqBBf-mC9pxB-J_v8ZWnlaL6gfbmLH0sB1TFywt-olmMDrO6paOcT2zgxUett4Wruq6P1HWHD67lTFW6c3KsfccEb2XjLtz0qpvxAd-HLgxT28sr_ZTindXtTPqLyUGxz-LITdTvq3XW24QXII8Q4lOpTWx6hgOtijhg1vQY?expiry=1705536000000&hmac=M_eBte2B5OSRVzueS8DXUZVpp7r69o2IoK0w88LyUVA)

You will be prompted to name and save your file. Give your Python file a name and click save.

![Image of saving the file helloworld.py in VS Code](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/jGOrTcXvSVSbLIkNh_EJlA_2361796da09343eaa7f4ea7b502bd3f1_gCCrqPLeFoiSms6yy-RgF9kVFfvjovbq7ctzxDf8RpV9PKWM9KutXETiAv8lsQ1LTqbjAdtfPFd84WFFJ9iAsL0w3fB6AhXxdypQA8Qg9oT84dhWDyTdzUjk54B-GFGPer5YOI-4Z6gPc-oQ79GYcY2-_N-Py5a4uUyyhg9tJe8wmU_la-gLOVuTLRY5WAU?expiry=1705536000000&hmac=OpeV-mQMKjOGrc9W_b7cxso3csJh-UKo85WdUqO7un0)

Your code will run and you will see its output here. 

![Image of the code output in VS Code. The output reads: Hello World!](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/0i-kPGw1TKm0_Zp8-78iOw_925bc8eb92e741179504793159b27df1_WVNosjVeKMtkrIhr_sXylRGhnExx6oyUgOTmLfUfo0v2orBIoz5B8ZfFsWHqzuhDveTRu0SE4Xpxls5IAMFxDmRRHGFTBJnC5JwAJXPffD30z_VHXu7ViYtU_MzSmPE4qt0SV5BeDM7mpnNbfbGzZugwIZotw6xWt-bkcHcJ3YTcLFYNOMBGw_q8RnGRX0U?expiry=1705536000000&hmac=GALSEn69Hpcpqvs5vLwfu3XS1D1UASsZP2ONejuInkQ)

Now  you know the basics of VS Code and how to use it! 

## **Key takeaways**

VS Code is an extremely robust source code editor. It uses [Intellisense](https://code.visualstudio.com/docs/editor/intellisense#:~:text=IntelliSense%20is%20a%20general%20term,%2C%20and%20%22code%20hinting.%22) technology which provides syntax highlighting and autocomplete for coding. VS code allows you to debug right in the editor with its interactive console. Overall, VS code is extremely interactive and customizable. There is also a large library of extensions that are easily integrated!

## **Resources for more information**

Here are some resources on what VS Code has to offer!

- This [resource](https://code.visualstudio.com/#powerful-debugging) provides an overview of VS Code.  

- This [resource](https://code.visualstudio.com/docs/languages/python) provides more information on using Python with VS Code and also includes a tutorial you can follow along with.

- This is the [extension library](https://marketplace.visualstudio.com/VSCode) for VS Code.
