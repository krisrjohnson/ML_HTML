# Creating an Encoder Decoder for Facial Landmarks to Face Output

Face swap is an auto-encoder of one encoder for two faces, A and B, with a decoder for each face. After training the auto-encoder, the actual swap happens by putting in face A into the encoder, but using face B's decoder, thereby swapping the faces.

For facial puppetry, the idea would be to train a decoder that transforms face A's facial landmarks (L of A, or LA) into face A. So to use the Merkel video as an example, we can take 400 frames and the facial landmarks from those frames and create a decoder. 

For v1, we can input directly into this decoder the facial landmarks from face B and output face A, completing our puppetry. This transformation would therefore account for head pose!

Additional items to take into account:
- transformation from LB -> LA
	- aka differences in facial geometry
	- v1 of transformation would be a basic geometric transform based off neutral poses
	- v2 could be an expression matching based off differences of landmark points from their neutrals, especially for eyes and nose (mouth and jaw too subject to talking)
- mouth resolution - could improve by using mouth splicing based off probability from the mouth facial landmarks alone
- blinking 
