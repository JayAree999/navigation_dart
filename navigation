import 'package:flutter/material.dart';
 
void main() => runApp(const MyApp());
 
class MyApp extends StatelessWidget {
  const MyApp({super.key});
 
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Navigator(
        initialRoute: '/',
        onGenerateRoute: (RouteSettings settings) {
          switch (settings.name) {
            case '/':
              return MaterialPageRoute(
                builder: (context) => MovieListScreen(),
              );
            case '/orange':
              return MaterialPageRoute(
                builder: (context) => OrangeScreen(),
              );
            case '/purple':
              return MaterialPageRoute(
                builder: (context) => PurpleScreen(),
              );
            case '/yellow':
              return MaterialPageRoute(
                builder: (context) => YellowScreen(),
              );
            case '/trailer':
              return MaterialPageRoute(
                builder: (context) => TrailerScreen(),
              );
            default:
              return MaterialPageRoute(
                builder: (context) => MovieListScreen(),
              );
          }
        },
      ),
    );
  }
}
 
 
class MovieListScreen extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return Scaffold(
      body: Center(
        child: Column(
          mainAxisAlignment: MainAxisAlignment.center,
          children: [
            Text("Movie", style: TextStyle(fontSize: 24)),
            Text("List", style: TextStyle(fontSize: 24)),
            Text("Screen", style: TextStyle(fontSize: 24)),
            SizedBox(height: 20),
            Container(
              padding: EdgeInsets.symmetric(horizontal: 20, vertical: 10),
              decoration: BoxDecoration(
                color: Colors.orange,
                borderRadius: BorderRadius.circular(20),
              ),
              child: TextButton(
                child: Text("Orange Button"),
                onPressed: () {
                  Navigator.pushNamed(context, '/orange');
                },
              ),
            ),
            SizedBox(height: 20),
            Container(
              padding: EdgeInsets.symmetric(horizontal: 20, vertical: 10),
              decoration: BoxDecoration(
                color: Colors.purple,
                borderRadius: BorderRadius.circular(20),
              ),
              child: TextButton(
                child: Text("Purple Button"),
                onPressed: () {
                  Navigator.pushNamed(context, '/purple');
                },
              ),
            ),
          ],
        ),
      ),
    );
  }
}class PurpleScreen extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(
        leading: IconButton(
          icon: Icon(Icons.arrow_back),
          onPressed: () => Navigator.pop(context),
        ),
        title: Text("Purple Screen"),
      ),
      body: Center(
        child: Column(
          mainAxisAlignment: MainAxisAlignment.center,
          children: [
            Text("Coming", style: TextStyle(fontSize: 24)),
            Text("Soon", style: TextStyle(fontSize: 24)),
            Text("Screen", style: TextStyle(fontSize: 24)),
            SizedBox(height: 20),
            Container(
              padding: EdgeInsets.symmetric(horizontal: 20, vertical: 10),
              decoration: BoxDecoration(
                color: Colors.deepPurple,
                borderRadius: BorderRadius.circular(20),
              ),
              child: TextButton(
                child: Text("Dark Purple Button"),
                onPressed: () {
                  Navigator.pushNamed(context, '/trailer');
                },
              ),
            ),
          ],
        ),
      ),
    );
  }
}
class OrangeScreen extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(
        leading: IconButton(
          icon: Icon(Icons.arrow_back),
          onPressed: () => Navigator.pop(context),
        ),
        title: Text("Orange Screen"),
      ),
      body: Center(
 
        child: Column(
          mainAxisAlignment: MainAxisAlignment.center,
          children: [
            Text("Text", style: TextStyle(fontSize: 24)),
            Text("Selection", style: TextStyle(fontSize: 24)),
            Text("Screen", style: TextStyle(fontSize: 24)),
            SizedBox(height: 20),
            Container(
              padding: EdgeInsets.symmetric(horizontal: 20, vertical: 10),
              decoration: BoxDecoration(
                color: Colors.yellow,
                borderRadius: BorderRadius.circular(20),
              ),
              child: TextButton(
                child: Text("Yellow Button"),
                onPressed: () {
                  Navigator.pushNamed(context, '/yellow');
                },
              ),
            ),
          ],
        ),
      ),
    );
  }
}
class YellowScreen extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(
        leading: IconButton(
          icon: Icon(Icons.arrow_back),
          onPressed: () => Navigator.pop(context),
        ),
        title: Text("Yellow  Screen"),
      ),
      body: Center(
        child: Column(
          mainAxisAlignment: MainAxisAlignment.center,
          children: [
            Text("Seat", style: TextStyle(fontSize: 24)),
            Text("Selection", style: TextStyle(fontSize: 24)),
            Text("Screen", style: TextStyle(fontSize: 24)),
          ],
        ),
      ),
    );
  }
}
 
class TrailerScreen extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(
        leading: IconButton(
          icon: Icon(Icons.arrow_back),
          onPressed: () => Navigator.pop(context),
        ),
        title: Text("Trailer Screen"),
      ),
      body: Center(
        child: Column(
          mainAxisAlignment: MainAxisAlignment.center,
          children: [
            Text("Trailer", style: TextStyle(fontSize: 24)),
            Text("Screen", style: TextStyle(fontSize: 24)),
          ],
        ),
      ),
    );
  }
}
