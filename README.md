# BoxBooru
*booru viewer for XBMC4Xbox.

![](/release/default.tbn)

Requires the latest version of XBMC (3.6-DEV-r33046 or later) from Xbins (as it has crucial TLS/SSL updates that allow this script to work).

![1](/screenshots/1.png)
![2](/screenshots/2.png)
![3](/screenshots/3.png)

## Supported Sites:
- Danbooru / 
- Gelbooru / Safebooru
- Konachan
- Probably many others that use Danbooru or Gelbooru code.

## Unsupported Sites:
- e926 (uses a different style of nested tags than other boorus)
- Sankaku (uses a different style of nested tags than other boorus)
- TBIB (doesn't relay a valid .json file)
- Others that use a very heavily modified version of the Danbooru/Gelbooru source.

## How To Use:
- Download latest release file, or "release" folder from the repository (delete update.zip if you do!).
- Extract the .zip file.
- Copy the "xBooru" folder to Q:/plugins/pictures
- Run the add-on and enjoy!

## Issues:
- Gelbooru-type source currently don't work due to a malformed URL issue.
- Danbooru only works with headers off (but introduces the issue of pagination causing a 403). Other Danbooru-type sources don't have this issue.
- You tell me.

# TODO: 
- Implement more than just "Recent Posts" and "Search".
