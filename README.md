# FreeCAD Teaching Assistant
Gives realtime or asynchronous recommendations, based on best practices, to parts created in FreeCAD Part Design. Aimes to increase the quality of community-created Part Design models.

Analyses a FreeCAD FCStd File containing at least one Part Design Body and gives hints, based on best practices, to the creator of the Part Design bodies.

This project is related to the FreeCAD-Tutorial-Generator and the FCViewer Platform and adds to the ecosystem of teaching resources for Beginner FreeCAD Users.


Types of best practices:
- Ordner of operations
- Prefered use of specific operations over other ones
- Prefered parameters for operations


Part Design best practices:
- [ ] Follow the plane, sketch, feature workflow
- [ ] Only use one closed wire per sketch
- [ ] First create all additive features and then all subtractive features, if possible
- [ ] Do not attach sketches to Topological Elements (Vertexes, Edges, Faces), always use Elements that dont change, such as the Origin for reference.
- [ ] Use Fillets, Chamfers and all other features that are inherently reliant on Topological Element references as the last features


More best practices to be added


Also take a look at and integrate into list: 
- [https://wiki.freecad.org/Best_Practices_with_SpreadSheets](https://wiki.freecad.org/Best_Practices_with_SpreadSheets)
- [https://forum.freecad.org/viewtopic.php?t=12738](https://forum.freecad.org/viewtopic.php?t=12738)
- [https://forum.freecad.org/viewtopic.php?t=15432](https://forum.freecad.org/viewtopic.php?t=15432)
- [https://www.youtube.com/playlist?list=PLP1rv37BojTd5NY3E_aqOWUe0uA8J-J1T](https://www.youtube.com/playlist?list=PLP1rv37BojTd5NY3E_aqOWUe0uA8J-J1T)


Brainstorming:
- Each best practice consists of a method that checks if the best practice has been applied, and a feedback text for success and fail.
  - For success, feedback text consists of a description of the best practice that has been applied and why it's important.
  - For fail, feedback text consists of a description of what could be improved and why its a problem.
- Return score in % and a badge (% intervalls), based on % of best practices that have been applied, each best practice having a weight (0.0 - 1.0) assigned to them.

-> How does the code structure look like for this application?


## Vision
- Integrate into FCViewer for asynchronous feedback.
- Integrate into FreeCAD for realtime feedback.

-> Increase the quality of community-created Part Design models.
