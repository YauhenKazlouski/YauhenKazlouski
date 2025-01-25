## Hi there 👋

    
    class IOSDeveloper {
      var name: String
      var lastName: String
      var role: String
      var languagesSpoken: [String]
    
      init() {
        self.name = "Yauhen"
        self.lastName = "Kazlouski"
        self.role = "IOS Developer"
        self.languagesSpoken = ["ru_BY", "en_US"]
      }

      func sayHi() {
        print("Thank you for stopping by! I hope you liked my profile.")
      }
    }
    
    let me = IOSDeveloper()
    me.sayHi()

