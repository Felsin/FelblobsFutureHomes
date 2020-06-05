#Felblob’s Future Homes
 
#Table of Contents

#Felblob’s Future Homes	1
#Table of Contents	1
#Introduction	1
#Requirements	2
#Download and Install	2
#Features	3
#Exhibit A – Host Data Key	3
#Exhibit B – Default Host Data	6
#Exhibit C – Host Data Explanations	9
#Resources	12
#Troubleshooting	13
#Please Note	14

#Introduction
Felblob’s Future Homes is a metaverse centric project delivering customizable scenes for deployment in Decentraland including Blender based 3d models and Typescript source code. The goal of the project is to learn about developing in the Ethereum ecosystem while growing the ecosystem through the deployment of my content through the blockchain metaverses.

All products under this project are released via MetaZone.io and are built to take advantage of the features that platform offers centered around the ability for less technical users to leverage the SDK. No technical knowledge is required besides the ability to edit a text field and manipulate an in game remote. The features include access to an in-game builder, and the ability to combine and customize multiple scenes, known as Meta’s, on the same parcel. MetaZone is a decentralized platform that gives access to an expanding library of player created content. 

Users deploy Metas using MetaZone.io and can adjust the Metadata of their purchase by editing fields under the Host Data section of their met’s. This allows for advanced customization of the meta’s with only a basic knowledge of the structure used in the Host Data File/Field.

Future products under the Felblob’s Future Homes project will include expansions to the existing meta as well as new metas and projects for Decentraland, Cryptovoxels and beyond.

#Requirements
1.	Computer capable of running Decentraland
2.	A parcel of land in Decentraland
3.	A MetaZone.io account
4.	A MetaMask or other Web3 Wallet
5.	MANA currency

#Download and Install
1.	Purchase Craftsman Home (Meta #1) – a custom 4 story home for use in Decentraland.
2.	Connect Web3 Wallet to MetaZone.io.
3.	Navigate to My Land - Select your parcel coordinates.
4.	Click the Edit Button (shaped as a Pencil).
                                           
5.	Expand the Host Data text field and adjust the fields as needed.
-Refer to Exhibit A to learn the structure of the Host Date. Only Fields adjustable only from within Host Data need to be adjusted under the Edit Button. NO fields need to be edited to launch the meta – you only need a copy of the data shown in Exhibit B to launch the meta for the first time. 
-Refer to Exhibit B if you need a copy of the default Host Data.
-Refer to Exhibit C if you want an explanation of what each field does.
6.	New Metas come with a copy of the Default Host Data shown in Exhibit B. Any time the Meta is updated and that updated includes changes to the structure of the Host Data (rare – only large features), the user will need to update their Host Data as shown here in steps 4-5.
7.	Click Grant (first time only) and then Deploy and allow 5 minutes for the scene to deploy to your parcel.
8.	Click visit to login to Decentraland at your parcel location.
9.	Use the MetaZone remote to adjust the location, scale, and rotation of your metas. The Meta button on the remote will switch between the different features of the meta.

#Features
Meta 1 – Craftsman Home:
Features –
1.	3 Stories & Accessible Roof
2.	Scale, Rotate, and Position the Model Using MetaZone Remote
3.	Adjust Features using Host Data (refreshes every minute in game)
4.	Animated Doors
5.	Audio Controller:
•	4 mood tracks
•	Custom streaming feed in Host Data
•	Prev/Next & Play/Pause
6.	5 Image Hooks W/ Frames
•	Custom links in Host Data
•	On/Off frames & On/Off images in Host Data
7.	5 NFT Hooks
•	Custom links in Host Data

#Exhibit A – Host Data Key
*Please do not be overwhelmed. This is only to help you if you are trying to find a specific field to adjust. The fields in Yellow can be adjusted easily using the MetaZone in game remote. The fields in Turqoise are adjusted only in Host Data and refer to items such as item links, stream links, and options such as making an image visible or not. Blue, Green and Teal fields are not ever changed. This is current as of V1.3.
Yellow = Adjustable field (In Game or through Host Data)
Turqoise = Adjustable field (Only in Host Data)
Blue = Name of field (DO NOT ADJUST)
Green = Category of adjustable fields (DO NOT ADJUST)
Teal = Name of Meta feature (DO NOT ADJUST)

 {
    "home": {
      "position": {"x":8, "y":0, "z":8},
      "rotation": {"x":0, "y":0, "z":0},
      "scale": {"x":1, "y":1, "z":1}
    },
    "audiopanel": {
      "position": {"x":8, "y":2.5, "z":8},
      "rotation": {"x":0, "y":0, "z":0},
      "scale": {"x":1, "y":1, "z":1},
    
    "stream": "https://www.bensound.com/bensound-music/bensound-anewbeginning.mp3"
  },
  "videopanel": {
    "position": {"x":7, "y":2, "z":8},
      "rotation": {"x":0, "y":0, "z":0},
      "scale": {"x":1, "y":1, "z":1},
      "videostream": "https://theuniverse.club/live/consensys/index.m3u8"
  },
  
  "imageframe1": {
    "position": {"x":3, "y":1, "z":7},
      "rotation": {"x":0, "y":0, "z":0},
      "scale": {"x":1, "y":1, "z":1},
      "images1": "https://lh3.googleusercontent.com/52N65amNm9Op-5y80GzS6xCZC06fKX3UuvGOC9G1MmARRxFnYxfolyyzl5GSHWbmzL5Qklu2VAu_WthFLh3reuw",
      "tog1Frame" : "true",
      "tog1Image" : "true"
    },
  
  "imageframe2": {
    "position": {"x":4, "y":1, "z":7},
      "rotation": {"x":0, "y":0, "z":0},
      "scale": {"x":1, "y":1, "z":1},
      "images2": "https://lh3.googleusercontent.com/52N65amNm9Op-5y80GzS6xCZC06fKX3UuvGOC9G1MmARRxFnYxfolyyzl5GSHWbmzL5Qklu2VAu_WthFLh3reuw",
      "tog2Frame" : "true",
      "tog2Image" : "true"
    },
  
  "imageframe3": {
    "position": {"x":5, "y":1, "z":7},
      "rotation": {"x":0, "y":0, "z":0},
      "scale": {"x":1, "y":1, "z":1},
      "images3": "https://lh3.googleusercontent.com/52N65amNm9Op-5y80GzS6xCZC06fKX3UuvGOC9G1MmARRxFnYxfolyyzl5GSHWbmzL5Qklu2VAu_WthFLh3reuw",
      "tog3Frame" : "true",
      "tog3Image" : "true"
    },
  
  "imageframe4": {
    "position": {"x":6, "y":1, "z":7},
      "rotation": {"x":0, "y":0, "z":0},
      "scale": {"x":1, "y":1, "z":1},
      "images4": "https://lh3.googleusercontent.com/52N65amNm9Op-5y80GzS6xCZC06fKX3UuvGOC9G1MmARRxFnYxfolyyzl5GSHWbmzL5Qklu2VAu_WthFLh3reuw",
      "tog4Frame" : "true",
      "tog4Image" : "true"
    },
  
  "imageframe5": {
    "position": {"x":7, "y":1, "z":7},
      "rotation": {"x":0, "y":0, "z":0},
      "scale": {"x":1, "y":1, "z":1},
      "images5": "https://wearable-api.decentraland.org/v2/collections/community_contest/wearables/cw_tuxedo_tshirt_upper_body/thumbnail",
      "tog5Frame" : "true",
      "tog5Image" : "true"
    },
  
    "nftframe1": {
      "position": {"x":2, "y":2, "z":8},
        "rotation": {"x":0, "y":0, "z":0},
        "scale": {"x":-1, "y":1, "z":1},
        "NFTimages1": "ethereum://0x06012c8cf97BEaD5deAe237070F9587f8E7A266d/558536",
        "NFTtog1" : "true"
      },
  
      "nftframe2": {
        "position": {"x":3, "y":2, "z":8},
          "rotation": {"x":0, "y":0, "z":0},
          "scale": {"x":-1, "y":1, "z":1},
          "NFTimages2": "ethereum://0x06012c8cf97BEaD5deAe237070F9587f8E7A266d/558536",
          "NFTtog2" : "true"
        },
  
        "nftframe3": {
          "position": {"x":4, "y":2, "z":8},
            "rotation": {"x":0, "y":0, "z":0},
            "scale": {"x":-1, "y":1, "z":1},
            "NFTimages3": "ethereum://0x06012c8cf97BEaD5deAe237070F9587f8E7A266d/558536",
            "NFTtog3" : "true"
          },
  
          "nftframe4": {
            "position": {"x":5, "y":2, "z":8},
              "rotation": {"x":0, "y":0, "z":0},
              "scale": {"x":-1, "y":1, "z":1},
              "NFTimages4": "ethereum://0x06012c8cf97BEaD5deAe237070F9587f8E7A266d/558536",
              "NFTtog4" : "true"
            },
  
            "nftframe5": {
              "position": {"x":6, "y":2, "z":8},
                "rotation": {"x":0, "y":0, "z":0},
                "scale": {"x":-1, "y":1, "z":1},
                "NFTimages5": "ethereum://0x06012c8cf97BEaD5deAe237070F9587f8E7A266d/558536",
                "NFTtog5" : "true"
              }
    
  }

#Exhibit B – Default Host Data
*This data can be copied directly into your Host Data, under the Edit Button, on the My Land tab of MetaZone.io. Using this data you can adjust all the position, rotation and scale of your objects. This is current as of V1.3. If your data is ever lost you can use this data to recover and use the MetaZone remote as normal. It will be updated for every release of the meta.
{
    "home": { 
      "position": {"x":8, "y":0, "z":8},
      "rotation": {"x":0, "y":0, "z":0},
      "scale": {"x":1, "y":1, "z":1}
    },
    "audiopanel": {
      "position": {"x":8, "y":2.5, "z":8},
      "rotation": {"x":0, "y":0, "z":0},
      "scale": {"x":1, "y":1, "z":1},
    
    "stream": "https://www.bensound.com/bensound-music/bensound-anewbeginning.mp3"
  },
  "videopanel": {
    "position": {"x":7, "y":2, "z":8},
      "rotation": {"x":0, "y":0, "z":0},
      "scale": {"x":1, "y":1, "z":1},
      "videostream": "https://theuniverse.club/live/consensys/index.m3u8"
  },
  
  "imageframe1": {
    "position": {"x":3, "y":1, "z":7},
      "rotation": {"x":0, "y":0, "z":0},
      "scale": {"x":1, "y":1, "z":1},
      "images1": "https://lh3.googleusercontent.com/52N65amNm9Op-5y80GzS6xCZC06fKX3UuvGOC9G1MmARRxFnYxfolyyzl5GSHWbmzL5Qklu2VAu_WthFLh3reuw",
      "tog1Frame" : "true",
      "tog1Image" : "true"
    },
  
  "imageframe2": {
    "position": {"x":4, "y":1, "z":7},
      "rotation": {"x":0, "y":0, "z":0},
      "scale": {"x":1, "y":1, "z":1},
      "images2": "https://lh3.googleusercontent.com/52N65amNm9Op-5y80GzS6xCZC06fKX3UuvGOC9G1MmARRxFnYxfolyyzl5GSHWbmzL5Qklu2VAu_WthFLh3reuw",
      "tog2Frame" : "true",
      "tog2Image" : "true"
    },
  
  "imageframe3": {
    "position": {"x":5, "y":1, "z":7},
      "rotation": {"x":0, "y":0, "z":0},
      "scale": {"x":1, "y":1, "z":1},
      "images3": "https://lh3.googleusercontent.com/52N65amNm9Op-5y80GzS6xCZC06fKX3UuvGOC9G1MmARRxFnYxfolyyzl5GSHWbmzL5Qklu2VAu_WthFLh3reuw",
      "tog3Frame" : "true",
      "tog3Image" : "true"
    },
  
  "imageframe4": {
    "position": {"x":6, "y":1, "z":7},
      "rotation": {"x":0, "y":0, "z":0},
      "scale": {"x":1, "y":1, "z":1},
      "images4": "https://lh3.googleusercontent.com/52N65amNm9Op-5y80GzS6xCZC06fKX3UuvGOC9G1MmARRxFnYxfolyyzl5GSHWbmzL5Qklu2VAu_WthFLh3reuw",
      "tog4Frame" : "true",
      "tog4Image" : "true"
    },
  
  "imageframe5": {
    "position": {"x":7, "y":1, "z":7},
      "rotation": {"x":0, "y":0, "z":0},
      "scale": {"x":1, "y":1, "z":1},
      
      "images5": "https://wearable-api.decentraland.org/v2/collections/community_contest/wearables/cw_tuxedo_tshirt_upper_body/thumbnail",
      "tog5Frame" : "true",
      "tog5Image" : "true"
    },
  
    "nftframe1": {
      "position": {"x":2, "y":2, "z":8},
        "rotation": {"x":0, "y":0, "z":0},
        "scale": {"x":-1, "y":1, "z":1},
        "NFTimages1": "ethereum://0x06012c8cf97BEaD5deAe237070F9587f8E7A266d/558536",
        "NFTtog1" : "true"
      },
  
      "nftframe2": {
        "position": {"x":3, "y":2, "z":8},
          "rotation": {"x":0, "y":0, "z":0},
          "scale": {"x":-1, "y":1, "z":1},
          "NFTimages2": "ethereum://0x06012c8cf97BEaD5deAe237070F9587f8E7A266d/558536",
          "NFTtog2" : "true"
        },
  
        "nftframe3": {
          "position": {"x":4, "y":2, "z":8},
            "rotation": {"x":0, "y":0, "z":0},
            "scale": {"x":-1, "y":1, "z":1},
            "NFTimages3": "ethereum://0x06012c8cf97BEaD5deAe237070F9587f8E7A266d/558536",
            "NFTtog3" : "true"
          },
  
          "nftframe4": {
            "position": {"x":5, "y":2, "z":8},
              "rotation": {"x":0, "y":0, "z":0},
              "scale": {"x":-1, "y":1, "z":1},
              "NFTimages4": "ethereum://0x06012c8cf97BEaD5deAe237070F9587f8E7A266d/558536",
              "NFTtog4" : "true"
            },
  
            "nftframe5": {
              "position": {"x":6, "y":2, "z":8},
                "rotation": {"x":0, "y":0, "z":0},
                "scale": {"x":-1, "y":1, "z":1},
                "NFTimages5": "ethereum://0x06012c8cf97BEaD5deAe237070F9587f8E7A266d/558536",
                "NFTtog5" : "true"
              }
    
  }

#Exhibit C – Host Data Explanations
*an explanation for each line of the Host Data file is found within the comment marks /** and **/.  This will also function as your Host Data although it is bulky and only suggested as a reference to better understand how to adjust fields within Host Data.
{
    "home": { /**Controls the House Model**/
      "position": {"x":8, "y":0, "z":8}, /**Positions the House Model**/
      "rotation": {"x":0, "y":0, "z":0}, /**Rotates the House Model**/
      "scale": {"x":1, "y":1, "z":1}     /**Scales the House Model**/
    },
    "audiopanel": { /**Controls the Audio Panel Model**/
      "position": {"x":8, "y":2.5, "z":8}, /**Positions the Model**/
      "rotation": {"x":0, "y":0, "z":0}, /**Rotates the Model**/
      "scale": {"x":1, "y":1, "z":1}, /**Scales the Model**/
    
    "stream": "URL" /** Controls the link to the Audio Stream **/
  },
  "videopanel": { /**Controls the Video Screen Model + Button**/
    "position": {"x":7, "y":2, "z":8}, /**Positions the Model**/
      "rotation": {"x":0, "y":0, "z":0}, /**Rotates the Model**/
      "scale": {"x":1, "y":1, "z":1}, /**Scales the Model**/
      "videostream": "URL"
  }, /** Controls the link to the Video Stream **/
  
  "imageframe1": { /**Controls the 1st Image and Frame Model**/
    "position": {"x":3, "y":1, "z":7}, /**Positions the Model**/
      "rotation": {"x":0, "y":0, "z":0}, /**Rotates the Model**/
      "scale": {"x":1, "y":1, "z":1}, /**Scales the Model**/
      "images1": "URL", 
/** Controls the link to the 1st Image **/
      "tog1Frame" : "true", 
/** Controls if 1st Frame On/Off using True/False **/
      "tog1Image" : "true"
/** Controls if 1st Image On/Off using True/False **/
    },
  
  "imageframe2": { /**Controls the 2nd Image and Frame Model**/
    "position": {"x":4, "y":1, "z":7}, /**Positions the Model**/
      "rotation": {"x":0, "y":0, "z":0}, /**Rotates the Model**/
      "scale": {"x":1, "y":1, "z":1}, /**Scales the Model**/
      "images2": "URL",
/** Controls the link to the 2nd Image **/
      "tog2Frame" : "true",
/** Controls if 2nd Frame On/Off using True/False **/
      "tog2Image" : "true"
/** Controls if 2nd Image On/Off using True/False **/

    },
  
  "imageframe3": { /**Controls the 3rd Image and Frame Model**/
    "position": {"x":5, "y":1, "z":7},/**Positions the Model**/
      "rotation": {"x":0, "y":0, "z":0},/**Rotates the Model**/
      "scale": {"x":1, "y":1, "z":1},/**Scales the Model**/

      "images3": " URL ",
/** Controls the link to the 3rd Image **/
      "tog3Frame" : "true",
/** Controls if 3rd Frame On/Off using True/False **/
      "tog3Image" : "true"
/** Controls if 3rd Image On/Off using True/False **/
    },
  
  "imageframe4": { /**Controls the 4th Image and Frame Model**/
    "position": {"x":6, "y":1, "z":7},/**Positions the Model**/
      "rotation": {"x":0, "y":0, "z":0},/**Rotates the Model**/
      "scale": {"x":1, "y":1, "z":1},/**Scales the Model**/
      "images4": " URL ",
/** Controls the link to the 4th Image **/
      "tog4Frame" : "true",
/** Controls if 4th Frame On/Off using True/False **/
      "tog4Image" : "true"
/** Controls if 4th Image On/Off using True/False **/
    },
  
  "imageframe5": { /**Controls the 5th Image and Frame Model**/
    "position": {"x":7, "y":1, "z":7},/**Positions the Model**/
      "rotation": {"x":0, "y":0, "z":0},/**Rotates the Model**/
      "scale": {"x":1, "y":1, "z":1},/**Scales the Model**/
    
      "images5": " URL ",
/** Controls the link to the 5th Image **/
      "tog5Frame" : "true",
/** Controls if 5th Frame On/Off using True/False **/
      "tog5Image" : "true"
/** Controls if 5th Image On/Off using True/False **/
    },
  
    "nftframe1": { /**Controls the 1st NFT Model**/
      "position": {"x":2, "y":2, "z":8},/**Positions the Model**/
        "rotation": {"x":0, "y":0, "z":0},/**Rotates the Model**/
        "scale": {"x":-1, "y":1, "z":1},/**Scales the Model**/
        "NFTimages1": " URL ",
/** Controls the link to the 1st NFT**/
        "NFTtog1" : "true"
/** Controls if 1st NFT On/Off using True/False **/
      },
  
      "nftframe2": { /**Controls the 2nd NFT Model**/
        "position": {"x":3, "y":2, "z":8},/**Positions the Model**/
          "rotation": {"x":0, "y":0, "z":0},/**Rotates the Model**/
          "scale": {"x":-1, "y":1, "z":1},/**Scales the Model**/
          "NFTimages2": " URL ",
/** Controls the link to the 2nd NFT**/
          "NFTtog2" : "true"
/** Controls if 2nd NFT On/Off using True/False **/

        },
  
        "nftframe3": { /**Controls the 3rd NFT Model**/
          "position": {"x":4, "y":2, "z":8},/**Positions the Model**/
            "rotation": {"x":0, "y":0, "z":0},/**Rotates the Model**/
            "scale": {"x":-1, "y":1, "z":1},/**Scales the Model**/
            "NFTimages3": " URL ",
/** Controls the link to the 3rd NFT**/
            "NFTtog3" : "true"
/** Controls if 3rd NFT On/Off using True/False **/
          },
  
          "nftframe4": { /**Controls the 4th NFT Model**/
            "position": {"x":5, "y":2, "z":8},/**Positions the Model**/
              "rotation": {"x":0, "y":0, "z":0},/**Rotates the Model**/
              "scale": {"x":-1, "y":1, "z":1},/**Scales the Model**/
              "NFTimages4": " URL ",
/** Controls the link to the 4th NFT**/
              "NFTtog4" : "true"
/** Controls if 4th NFT On/Off using True/False **/
            },
  
            "nftframe5": { /**Controls the 5th NFT Model**/
              "position": {"x":6, "y":2, "z":8},/**Positions the Model**/
                "rotation": {"x":0, "y":0, "z":0},/**Rotates the Model**/
                "scale": {"x":-1, "y":1, "z":1},/**Scales the Model**/
                "NFTimages5": " URL ",
/** Controls the link to the 5th NFT**/
                "NFTtog5" : "true"
/** Controls if 5th  NFT On/Off using True/False **/
              }
    
  }




#Resources

Trello Roadmap
MetaZone Setup Video
Felblob.com
MetaZone.io
Uniswap (Purchase MANA)
Decentraland.org

#Troubleshooting

1.	I cannot see the MZ remote or Icon when logging in. 
SOLUTION: Ensure you are using the most recent Host Data show in Exhibit B. If still not functioning, try redeploying. If this fails contact @Felblob via the resources above for assistance.
2.	My Image link is not working. 
SOLUTION: Press F12 to view the Console in your web browser. You may see an error message related to CORS. DCL is strict and needs your image to be CORS appropriate. Please use this format to attempt to bypass CORS. If that does not function please use a different hosting source and ensure the default Host Data image links still function in your scene. Here is information on the sound requirements:
“The audio in the source must be in one of the following formats: .mp3, ogg, or aac. The source must also be an https URL (http URLs aren’t supported), and the source should have CORS policies (Cross Origin Resource Sharing) that permit externally accessing it. If this is not the case, you might need to set up a server to act as a proxy and expose the stream in a valid way.”
URL format: https://cors-anywhere.herokuapp.com/YOUR_IMAGE_URL_HERE.
3.	My NFT link is not working.
SOLUTION: Ensure you are using the correct NFT format. The frame around the NFT will only show if your wallet possesses the token.
URL format: ethereum://0x06012c8cf97BEaD5deAe237070F9587f8E7A266d/558536
The example above fetches an NFT with the contract address 0x06012c8cf97BEaD5deAe237070F9587f8E7A266d, and the specific identifier 558536. The corresponding asset asset can be found in OpenSea at https://opensea.io/assets/0x06012c8cf97BEaD5deAe237070F9587f8E7A266d/558536.
4.	My Video link is not working. 
SOLUTION: Refer to #2 for information on CORS appropriate links and hosting sources.
5.	I don’t know how to change my mood tracks, play video, or display audio.
SOLUTION: All of this is controlled in game via the MetaZone remote and the Audiopanel meta. It contains buttons for all the functions that can be controlled from within DCL. 
6.	I can’t see any of my scene once I deploy your meta.
SOLUTION: Metas do not work with builder scenes. The MZ developers are working to allow the import of builder scenes / assets into MetaZone. I have built my Meta’s to include as many base features of the builder as possible so that the user does not feel they are giving up functionality. But, this is currently a disadvantage to using a meta, hopefully outweighed greatly by the flexibility of the MZ system. 

#Please Note
Using MetaZone currently restricts the user from adding any objects from the builder or combining a meta with an existing scene from the builder. This feature is in the works by the development team.
Products offered under Felblob’s Future Homes cannot be reproduced without express permission and are meant to produce revenue to further advance the efforts of the project. Please ask permission if you would like to use any assets from the project or contribute in any way. 


Contact Me: 
@Felblob (Twitter)
@Felblob#5247 (Discord)

Thank you, Felblob


