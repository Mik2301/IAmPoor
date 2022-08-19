# IAmPoor
import 'package:flutter/material.dart';

void main() {
  runApp(MaterialApp(
      home: Scaffold(
          backgroundColor: Colors.brown,
          appBar: AppBar(
              title: const Center(child: Text('I Am Poor')),
              backgroundColor: Colors.brown[900]),
          body: const Center(
              child: Image(image: AssetImage('Images/IAmPoor.jpg'))))));
}
