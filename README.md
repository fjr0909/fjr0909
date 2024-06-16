- 👋 Hi, I’m @fjr0909
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
fjr0909/fjr0909 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
// 3 endpoint receive()
/**
  @notice Function to receive state from the Dojima chain and execute data.
  @params stateId unique identifier of the state.
  @params stateData contact call data.
**/

function onStateReceive(uint256 stateId, bytes calldata stateData) external;
