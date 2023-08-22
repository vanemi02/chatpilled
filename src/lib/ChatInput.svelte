<input type="text" name="chatInput" id="">

<style>
  input {
    position: absolute;
    width: 95%;
    bottom: 1em;
    left: 50%;
    transform: translateX(-50%);
    
    margin: 0;
    
    padding-inline: 0.8em;
    padding-block: 0.5em;

    background-color: var(--background-color-2);
    color: var(--text-color);
    
    border: none;
    transition: background-color 100ms ease-in-out;
    border-radius: 100px;
    outline: none;
  }
  
  input:focus, :hover {
    background-color: var(--background-color-3);
  }

</style>