## Description

SMS service for phone number verification.

## Endpoints

* **/verify-phone**
* **/verify**

## Usage
* Send a post request to **/verify-phone** with **phone number** as **x-www-form-urlencoded** to send an a phone verification OTP to the phone number. The request should call a **__phone__** parameter in the body.

* To verify the token sent to the phone number, send a **POST** request to **/verify** to verify the phone number.