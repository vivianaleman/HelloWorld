# HelloWorld
Challenge for Chiedo 1
function tick(){
const element = (
  <div>
  <h1> Hello, world!</h1>
  <h2>{new Date().toLocaleTimeString()}</h2>
  </div>
  );
   ReactDOM.render(element, document.getElementById('root'));
}

  setInterval(tick,1000);   

