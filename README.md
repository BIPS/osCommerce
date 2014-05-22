Copyright (C) 2013-2014 by BIPS

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

About
=====
+ Bitcoin payments via BIPS for osCommerce.
+ Version 0.1
	
System Requirements:
===================
+ BIPS API, Merchant Secret
+ Curl PHP Extension
+ JSON Encode
  
Configuration Instructions:
==========================
    1. Upload files to your osCommerce installation.
    2. Go to your osCommerce administration. Modules -> Payment -> Install Module (44) then Bitcoins via BIPS. Click Install Module.
    3. In BIPS Callback URL (https://bips.me/merchant) Enter the link to your callback of BIPS Payment Module. (http://YOUR_OSCOMMERCE_URL/bips_callback.php)
    4. Enter a strong Secret in Merchant SECRET.
    5. In module settings "API" <- set your BIPS API Key, which can be generate under API Keys, Invoice.
    6. In module settings "Secret" <- Enter your BIPS Merchant Secret.

### Tested with:

+ osCommerce version 2.3.3