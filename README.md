body {
    font-family: Arial, sans-serif;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background-color: #f4f4f4;
}

.container {
    width: 50%;
    background: #fff;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.progress-bar {
    display: flex;
    justify-content: space-between;
    margin-bottom: 30px;
    position: relative;
}

.progress {
    position: absolute;
    top: 50%;
    left: 0;
    height: 5px;
    background: #4caf50;
    transition: width 0.3s;
}

.step {
    width: 30px;
    height: 30px;
    background: #ddd;
    border-radius: 50%;
    display: flex;
    justify-content: center;
    align-items: center;
    z-index: 1;
}

.step.active {
    background: #4caf50;
    color: #fff;
}

.form-step {
    display: none;
}

.form-step-active {
    display: block;
}

button {
    padding: 10px 20px;
    margin: 10px 0;
    border: none;
    background: #4caf50;
    color: #fff;
    cursor: pointer;
    border-radius: 5px;
}

button:disabled {
    background: #ccc;
    cursor: not-allowed;
}
body {
    font-family: Arial, sans-serif;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background-color: #f4f4f4;
}

.container {
    width: 50%;
    background: #fff;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.inputWrapper {
    display: flex;
    align-items: center;
    margin-bottom: 10px;
}

input[type="text"] {
    flex: 1;
    padding: 10px;
    margin-right: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
}

button {
    padding: 10px 20px;
    border: none;
    background: #4caf50;
    color: #fff;
    cursor: pointer;
    border-radius: 5px;
}

button.removeButton {
    background: #f44336;
}

button:disabled {
    background: #ccc;
    cursor: not-allowed;
}
