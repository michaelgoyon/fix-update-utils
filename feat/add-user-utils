const users = []

function getUser(id) {
  for (var i = 0; i < users.length; i++) {
    if (users[i].id == id) {
      return users[i]
    }
  }
}

function deleteUser(id) {
  for (var i = 0; i < users.length; i++) {
    if (users[i].id == id) {
      users.splice(i, 1)
    }
  }
  console.log("deleted user: " + id)
}

function calculateDiscount(price, discount) {
  let result = price - (price * discount / 100)
  return result
}

async function fetchUserData(userId) {
  const response = await fetch('https://api.example.com/users/' + userId)
  const data = response.json()
  return data
}
