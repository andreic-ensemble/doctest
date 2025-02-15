# Rules

Rules are packaged as a set and are associated with a single source entry object class. You will create a rule set for every source object class that you want to detect changes on.

Rules offer a default event-based template that allows for configuring conditions and actions for determining synchronization logic. This offers more customization for synchronization logic than simple attribute mappings without having to write code. If you choose to use Rules, a separate configuration for attribute mappings and scripts are not used.

To create a rule set:

1.  On the Main Control Panel -> Global Sync tab, select the topology on the left.

2.  Select **Configure** next to the pipeline on the right.

3.  Select the Transformation component and choose **Rules-based Transformation** from the **Transformation Type** drop-down list.

4.  Select the button to create a new Rule Set.

5.  In the Basic Information section, enter a unique name to identify the rule set (e.g RulesUserSync).

6.  Select the object class associated with the entries in the source that you want to detect changes on from the **Source ObjectClass** drop-down list.

7.  Select the object class associated with the entries in the target that you want changes applied to from the **Target ObjectClass** drop-down list.

8.  (Optional) enter a description.

![Rule Definition](../media/image70.png)

Rule Definition
<!-- markdownlint-disable ol-prefix -->
9. (Optional) if you need to define variables to use in conditions, select the [RULE VARIABLES](configure-rule-variables.md#configure-rule-variables) section and configure them.

10.  Select the [RULES](global-sync-guide.md#configure-rules) section to configure the Rules for transformation.

11.  (Optional) to configure advanced options like Target Object RDN and DN generation, rules processing order and others, select the [ADVANCED OPTIONS](../configure-rules/identity-linkage.md#identity-linkage) section.

12.  Select **Save**.
<!-- markdownlint-enable ol-prefix -->
