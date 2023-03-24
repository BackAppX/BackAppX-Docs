# Installation and Setup

To get started with the BackAppX Dart SDK, you'll need to follow these steps:

1 - Sign up for a BackAppX account and create a new app.<br>
2 - Generate a BackAppX API key for your app.<br>
3 - Install the BackAppX Dart SDK in your mobile app project using pub.<br>

#### Here's an example of how to install the BackAppX Dart SDK in kotlin/java project:

```kotlin
implementation 'com.BackAppX:BackAppX-sdk:1.0.0'
```
#### Create a new instance of the BackAppX client and pass in your API key:

```kotlin
import com.BackAppX.sdk.BackAppXClient;
BackAppXClient client = new BackAppXClient("YOUR_API_KEY_HERE");
```