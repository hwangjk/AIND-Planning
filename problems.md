problems.md


1. heuristic ignore_precond:

	shoule consider if an action causes multiple goal conditions?
		Plane carrying a cargo to an airport
			Cargo at Airport goal
				and 
			Plane at Airport goal


	should check if goal state reached to terminate heuristic run?

	Should consider an action undoing a goal condition for sake of another?

		Plane carrying a cargo to an airport for Cargo Goal
		But, Plane was already goal state at the init. airport


TASKS TODO:

- `PlanningGraph.add_action_level` method
- `PlanningGraph.add_literal_level` method
- `PlanningGraph.inconsistent_effects_mutex` method
- `PlanningGraph.interference_mutex` method
- `PlanningGraph.competing_needs_mutex` method
- `PlanningGraph.negation_mutex` method
- `PlanningGraph.inconsistent_support_mutex` method
- `PlanningGraph.h_levelsum` method
