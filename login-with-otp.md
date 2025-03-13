# Login with OTP

## Login Node&#x20;

gw-ui01.sdfarm.kr



## Accessing via Terminal on Linux or Mac

To connect to the GSDC UI server using a terminal on Linux or Mac after setting up OTP, you need to undergo two authentication steps.&#x20;

The first authentication is carried out using the regular password, and the second authentication requires the verification of the issued OTP token.



First Authentication:

<pre data-overflow="wrap"><code><strong>First Factor: [Enter your regular password here]
</strong></code></pre>



Second Authentication :

```
Second Factor: [Enter the OTP code here]
```



\<ex>

```sh
$> ssh -p [port number] test_ipa@[target UI's hostname]
(test_ipa@[UI]) First Factor: [Enter regular password]
(test_ipa@[UI]) Second Factor: [Enter OTP code]
Last login: [last login details]
[test_ipa@[UI] ~]$
```





## Connecting via MobaXterm on Windows

After setting up OTP, to access the GSDC UI server, two authentication steps are required. The first authentication is done as usual with a password. The second authentication requires the OTP token you've been issued.



First Authentication :

{% code overflow="wrap" %}
```
First Factor: [Enter regular password here]
```
{% endcode %}



Second Authentication :

```
Second Factor: [Enter OTP code here]
```



\<ex>

<figure><img src=".gitbook/assets/SE-c6700a9b-0f39-4891-ab3c-a066d98dfb96 (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/스크린샷_2023-10-18_오후_6.15.01 (1).png" alt=""><figcaption></figcaption></figure>



## Using FileZilla for Connection

After setting up OTP, to connect to the GSDC UI server, you need to perform two authentication steps. The first authentication is carried out as usual using password verification, and the second authentication requires the verification of the issued OTP token.



First Authentication :

{% code overflow="wrap" %}
```
First Factor: [Enter regular password here]
```
{% endcode %}



Second Authentication :

```
Second Factor: [Enter OTP code here]
```



\<ex>

<figure><img src=".gitbook/assets/스크린샷 2023-10-19 오후 5.30.25.png" alt=""><figcaption></figcaption></figure>

\#Logon Type must be set to "Interactive".



## Connecting using Xshell



After setting up OTP, to access the GSDC UI server, you must undergo two authentication steps. The first authentication is the usual password authentication, and the second is the authentication using the issued OTP token.&#x20;



First Authentication :

{% code overflow="wrap" %}
```
First Factor: [Enter regular password here]
```
{% endcode %}



Second Authentication :

```
Second Factor: [Enter OTP code here]
```



\<ex>

<figure><img src=".gitbook/assets/스크린샷 2023-10-19 오후 6.04.29.png" alt=""><figcaption></figcaption></figure>

⌗ Authentication method must be changed to Keyboard Interactive.

##

## Caution

* The OTP code changes over time. Therefore, you must use a new OTP code every time you connect.&#x20;
* Incorrect OTP authentication may result in a denied connection. Please double-check your input information and try again.
