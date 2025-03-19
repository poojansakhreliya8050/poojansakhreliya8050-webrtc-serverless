# WebRTC One-to-One Video Chat (Serverless)

This is a simple one-to-one video chat application built using WebRTC without a backend server. The connection is established manually by exchanging offer and answer between two users.

## Features
- One-to-one video call using WebRTC
- Manual SDP offer/answer exchange
- No backend server required

## How It Works
1. **User 1 (Sender) initiates the call:**
   - Click on the "Create Offer" button to generate an SDP offer.
   - Copy the generated offer and share it manually with the receiver.

2. **User 2 (Receiver) joins the call:**
   - Paste the received offer in the first input box.
   - Click on "Create Answer" to generate an SDP answer.
   - Copy the generated answer and share it manually with the sender.

3. **User 1 completes the connection:**
   - Paste the received answer in the second input box.
   - Click on the "Start Connection" button to establish the WebRTC connection.

## Installation & Usage
1. Clone the repository:
   ```sh
   git clone https://github.com/poojansakhreliya8050/poojansakhreliya8050-webrtc-serverless.git
   ```
2. Navigate to the project folder:
   ```sh
   cd poojansakhreliya8050-webrtc-serverless
   ```
3. Open `index.html` in a browser.

## Technologies Used
- WebRTC (RTCPeerConnection, getUserMedia)
- JavaScript
- HTML & CSS

## Screenshots
![image](https://github.com/user-attachments/assets/1b0fc6ce-849a-412d-ab37-f31af7546e27)


## Limitations
- Manual exchange of offer/answer required
- No signaling server (must use another method to share SDP data)

## Future Improvements
- Implement a signaling server for automatic SDP exchange
- Enhance UI/UX for a better experience
- Add support for additional features like chat

## Author
[Poojan Sakhreliya](https://github.com/poojansakhreliya8050)

