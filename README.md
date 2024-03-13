import 'package:flutter/material.dart';

void main() {
  runApp(MaterialApp(
    title: "My First Page",
    color: Colors.red,
    debugShowCheckedModeBanner: false,
    theme: ThemeData(
        primarySwatch: Colors.red,
        brightness: Brightness.light,
        fontFamily: "Ind"),
    home: Scaffold(
      backgroundColor: Colors.white,
      appBar: AppBar(
        title: Text('First Screen'),
        leading: Icon(Icons.home),
        centerTitle: true,
        backgroundColor: Colors.green,
      ),
      body: Center(
          child: Icon(
        Icons.query_builder,
        color: Colors.blue,
        size: 40.0,
      )),
      floatingActionButton: FloatingActionButton(
          child: Icon(Icons.favorite),
          backgroundColor: Colors.green,
          onPressed: null),
    ),
  ));
}
