<div>
  <h1 id="name">John Doe</h1>
  <img id="profile-pic" src="https://www.example.com/profile-pic.jpg" alt="Profile Picture">
</div>
#name {
  animation: greeting 2s ease-in-out;
}

#profile-pic {
  animation: bounce 1s ease-in-out;
}

@keyframes greeting {
  0% {
    transform: scale(1);
  }
  50% {
    transform: scale(1.2);
  }
  100% {
    transform: scale(1);
  }
}

@keyframes bounce {
  0% {
    transform: translateY(0);
  }
  50% {
    transform: translateY(-10px);
  }
  100% {
    transform: translateY(0);
  }
}
