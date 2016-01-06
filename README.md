# Simpl Android SDK

## Version 1.0.14 Release Notes
1. Fixed loader related issue

## Version 1.0.13 Release Notes
1. Fixed bug related with listeners for some edge cases

## Version 1.0.12 Release Notes
1. Update proguard config for the SDK
2. Removed some overlapping dependency

## Version 1.0.11 Release Notes
1. Fixed loader issues

## Version 1.0.10 Release Notes
1. Minor bug fixes
2. Loader related UI fixes
3. Now handles mailto url actions

## Version 1.0.9 Release Notes
1. ProgressDialog is shown for the webview url loading

## Version 1.0.8 Release Notes
1. onCancelled callback is removed from the listener
2. Automatic closing of the confirmation page is added. The default time is 3 seconds.
 
## Version 1.0.7 Release Notes
1. onCancelled callback is deprecated now. That code block will never be called during the SDK flow.

## Version 1.0.6 Release Notes
1. Added authorizeTransaction method for using custom button/view to trigger transaction authorization.

## Version 1.0.5 Release Notes
1. Bug fixes 
   - Fixed the button height issue related with Cynogenmod.
   - Fixed the dpToPx conversion for simpl__simpleButtonHeight attribute 
   - Fixed the scaling issue related with Simpl logo on SimplButton
   - Fixed the scrolling issue on the account activation page
2. Added ripple effect on SimplButton (for LOLLIPIP+ devices)i
3. simpl_separatorColor is now deprecated. simpl_buttonShadowColor will be used as separator color from 1.0.5.

## Version 1.0.4 Release Notes
1. Removed Crittercism and shifted error logging on Airbrake
2. Reduced size of SDK : Now its 188 KB including all dependencies.

## Version 1.0.3 Release Notes
1. Reduced Target Compile SDK version to 22.0.1
2. Reduced Build Tool version to 22.0.1
3. Super slim SDK, no thrid party library dependency.
4. Elaborated error messages sent through onError.
5. Added onCancelled callback to detect if user has cancelled the transaction in-between.

## Version 1.0.2 Release Notes
1. Added customization method and styled attribute for SimplButton title text.
2. Added ```SimplSession```, a simple storage system across the activites.

## Version 1.0.1 Release Notes
1. Added customizations support to Buy with Simpl button
2. Customizations can be done using Java methods of SimplButton or using stylable provided with verison 1.0.1.

## Version 1.0.0 Release Notes
1. First production release
2. Web view based flow
3. Automatic OTP detection


# Licence
Copyright © 2015, Get Simpl Technologies Private Limited
All rights reserved.

This software is proprietary, commercial software. All use must be licensed. The licensee is given the right to use the software under certain conditions, but is restricted from other uses of the software, such as modification, further distribution, or reverse engineering. Unauthorized use, duplication, reverse engineering, any form of redistribution, or use in part or in whole other than by prior, express, written and signed license for use is subject to civil and criminal prosecution. If you have received this file in error, please notify the copyright holder and destroy this and any other copies as instructed.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDER ON AN "AS IS" BASIS AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED, AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

