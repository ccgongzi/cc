# cc
git clone https://github.com/SheepTester/primitive-cloud-server.git
cd primitive-cloud-server
npm install
npm start
// client -> server
{ "method": "handshake", "project_id": "104" }

// server -> client
{ "method": "set", "name": "☁ cool cloud variable", "value": "45643563456" }
{ "method": "set", "name": "☁ epic cloud variable", "value": "10239489031" }
{ "method": "set", "name": "☁ newish variable", "value": "0" }
