Overview
========

.. include:: ../_static/badges/allplans-cloud-selfhosted.rst
  :start-after: :nosearch:

Mattermost Playbooks is a collaboration tool that defines a repeatable process to enable teams to achieve specific and predictable outcomes. With playbooks, development teams can orchestrate prescribed workflows and define, streamline, and document complex, recurring operations.

Mattermost Playbooks is enabled by default for Mattermost self-hosted and Mattermost Cloud workspaces. You can access Playbooks via the product menu in the top-left corner of Mattermost.

To find all playbook runs, open **Product menu > Playbooks**, and then select any playbook name. Next, select **Runs** from the navigation bar, then choose a run to view its overview. Select **Go to channel** to open the run’s channel.

Each playbook represents a recurring outcome or specific goal that your teams collaborate on to achieve, such as service outage recovery or customer onboarding. 

Playbooks are made up of:

- **Checklists**: The list of tasks to be completed for the run. `Checklists </playbooks/customize-a-playbook.html#make-checklists>`_ can be edited ad-hoc during a run.
- **Templates**: `Templates </playbooks/overview.html#templates>`_ for frequently-used actions such as updates and reminders. You can create your own templates or use default ones.
- **Actions**: `Automation options </playbooks/customize-a-playbook.html#actions>`_ for inviting members, creating webhooks, editing welcome messages, and more.
- **Permissions**: Manage :doc:`permissions </playbooks/share-and-collaborate>` at a channel and a playbook level.

Teams run a playbook every time they want to orchestrate people, tools, and data to achieve that outcome as quickly as possible while providing visibility to stakeholders. 

For participants, it prescribes processes such as task checklists, status updates, and retrospective reports. For integrated tools, it configures the triggers to perform automated actions. And for stakeholders, it provides a single pane of glass for visibility into each run as well as aggregate insights over time.

Playbooks also allow teams to incorporate learnings from the retrospective to tweak and improve the playbook with every iteration.

What's a playbook?
------------------

A playbook is a repeatable process that is refined over time. For example, the steps you follow when dealing with an outage, a software release, or welcoming a new member of your team can all be made into a playbook.

Playbook usage can be measured and adapted, and you can follow a playbook each time it's run.

What's a run?
-------------

A run is the execution of the steps in a playbook. When a playbook is run, the process begins in a channel. Members of a playbook can view the run's progress in the run details page or they can participate in the run channel.

When the process is completed, the run is ended. A retrospective can be run and the channel can be archived.

Keywords
--------

It's important to make it easy to start a run. One way to do this is by setting up keywords. These keywords prompt a user to start the run when they're used. In the incident response playbook, the keywords are specific to critical incidents, for example ``sev-1`` and ``#incident``. It's unlikely that someone would use those terms in general conversation and, even if they do, they can elect not to start the playbook run when prompted.

Welcome message
---------------

Create a welcome message so that when members join your run, it's easy for them to see where they're needed and where to find the relevant information. This is especially important during a time-sensitive incident to eliminate confusion and help members ramp up quickly.

Tasks and checklists
--------------------

Tasks and checklists are the foundation of a template and a workflow. In an incident, it's critical to get stakeholders together as soon as possible, so one of the first tasks is to add the on-call engineer to the channel, followed by starting a bridge call. When you're setting up these tasks, you can add slash commands, at-mentions, and integrations with tools such as Zoom to make the initiation as seamless as possible.

Status updates
--------------

Regular updates are important communication tools, especially in the middle of an incident like an outage. Channels can get very busy and overwhelming, and if you have more than one incident at a time, it's often too noisy for stakeholders to keep track of everything.

Use the **Broadcast update to other channels** option to cut through the noise and share critical information with both channel members and other users in a dedicated channel.

Additionally, set a timer that issues a reminder for updates to be shared.

Retrospective
-------------

When an incident is over, create a retrospective that captures the impact of the event. You can also add metrics, such as how long it took to resolve the incident, which you can apply to other, similar incidents to see where you can improve and refine your workflows.
