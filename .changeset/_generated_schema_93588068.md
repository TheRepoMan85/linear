---
"@linear/sdk": major
---


feat(schema): [breaking] Type 'AttachmentArchivePayload' was removed (AttachmentArchivePayload)

feat(schema): [breaking] Type 'NotificationChannelPreferencesInput' was removed (NotificationChannelPreferencesInput)

feat(schema): [breaking] Type 'ProjectLinkCreateInput' was removed (ProjectLinkCreateInput)

feat(schema): [breaking] Type 'ProjectLinkPayload' was removed (ProjectLinkPayload)

feat(schema): [breaking] Type 'ProjectLinkUpdateInput' was removed (ProjectLinkUpdateInput)

feat(schema): [breaking] Field 'contentData' (deprecated) was removed from object type 'Document' (Document.contentData)

feat(schema): [breaking] Field 'contentData' (deprecated) was removed from object type 'DocumentSearchResult' (DocumentSearchResult.contentData)

feat(schema): [breaking] Field 'attachmentArchive' (deprecated) was removed from object type 'Mutation' (Mutation.attachmentArchive)

feat(schema): [breaking] Field 'projectLinkCreate' was removed from object type 'Mutation' (Mutation.projectLinkCreate)

feat(schema): [breaking] Field 'projectLinkDelete' was removed from object type 'Mutation' (Mutation.projectLinkDelete)

feat(schema): [breaking] Field 'projectLinkUpdate' was removed from object type 'Mutation' (Mutation.projectLinkUpdate)

feat(schema): [breaking] Field 'links' (deprecated) was removed from object type 'Project' (Project.links)

feat(schema): [breaking] Field 'creator' was removed from object type 'ProjectLink' (ProjectLink.creator)

feat(schema): [breaking] Field 'project' was removed from object type 'ProjectLink' (ProjectLink.project)

feat(schema): [breaking] Field 'descriptionData' (deprecated) was removed from object type 'ProjectMilestone' (ProjectMilestone.descriptionData)

feat(schema): [breaking] Field 'links' (deprecated) was removed from object type 'ProjectSearchResult' (ProjectSearchResult.links)

feat(schema): [breaking] Field 'projectLink' was removed from object type 'Query' (Query.projectLink)

feat(schema): [breaking] Field 'projectLinks' was removed from object type 'Query' (Query.projectLinks)

feat(schema): [breaking] Field 'notificationPreferences' was removed from object type 'UserSettings' (UserSettings.notificationPreferences)

feat(schema): [breaking] Field 'subscribedToUnreadNotificationsReminder' (deprecated) was removed from object type 'UserSettings' (UserSettings.subscribedToUnreadNotificationsReminder)

feat(schema): [breaking] Input field 'notificationPreferences' was removed from input object type 'UserSettingsUpdateInput' (UserSettingsUpdateInput.notificationPreferences)

feat(schema): [breaking] Input field 'subscribedToUnreadNotificationsReminder' was removed from input object type 'UserSettingsUpdateInput' (UserSettingsUpdateInput.subscribedToUnreadNotificationsReminder)

feat(schema): [breaking] Input field 'UserSettingsUpdateInput.notificationChannelPreferences' changed type from 'NotificationChannelPreferencesInput' to 'PartialNotificationChannelPreferencesInput' (UserSettingsUpdateInput.notificationChannelPreferences)

feat(schema): [dangerous] Input field 'issueLabels' was added to input object type 'InheritanceEntityMapping' (InheritanceEntityMapping.issueLabels)

feat(schema): [dangerous] Input field 'updateReminderFrequencyInWeeks' was added to input object type 'InitiativeUpdateInput' (InitiativeUpdateInput.updateReminderFrequencyInWeeks)

feat(schema): [dangerous] Input field 'updateRemindersDay' was added to input object type 'InitiativeUpdateInput' (InitiativeUpdateInput.updateRemindersDay)

feat(schema): [dangerous] Input field 'updateRemindersHour' was added to input object type 'InitiativeUpdateInput' (InitiativeUpdateInput.updateRemindersHour)

feat(schema): [dangerous] Argument 'url: String' added to field 'Mutation.attachmentLinkZendesk' (Mutation.attachmentLinkZendesk.url)

feat(schema): [dangerous] Input field 'containsIgnoreCaseAndAccent' was added to input object type 'NullableStringComparator' (NullableStringComparator.containsIgnoreCaseAndAccent)

feat(schema): [dangerous] Input field 'updateReminderFrequencyInWeeks' was added to input object type 'ProjectUpdateInput' (ProjectUpdateInput.updateReminderFrequencyInWeeks)

feat(schema): [dangerous] Input field 'updateRemindersDay' was added to input object type 'ProjectUpdateInput' (ProjectUpdateInput.updateRemindersDay)

feat(schema): [dangerous] Input field 'updateRemindersHour' was added to input object type 'ProjectUpdateInput' (ProjectUpdateInput.updateRemindersHour)

feat(schema): [dangerous] Input field 'containsIgnoreCaseAndAccent' was added to input object type 'SourceTypeComparator' (SourceTypeComparator.containsIgnoreCaseAndAccent)

feat(schema): [dangerous] Input field 'containsIgnoreCaseAndAccent' was added to input object type 'StringComparator' (StringComparator.containsIgnoreCaseAndAccent)

feat(schema): [dangerous] Input field 'containsIgnoreCaseAndAccent' was added to input object type 'StringItemComparator' (StringItemComparator.containsIgnoreCaseAndAccent)

feat(schema): [non_breaking] Type 'CustomerImport' was added (CustomerImport)

feat(schema): [non_breaking] Field 'CustomerNeed.url' description changed from 'Optional URL to the source of the customer need. Used when manually creating a need.' to '[DEPRECATED] Optional URL to the source of the customer need. Used when manually creating a need.' (CustomerNeed.url)

feat(schema): [non_breaking] Field 'CustomerNeed.url' is deprecated (CustomerNeed.url)

feat(schema): [non_breaking] Field 'CustomerNeed.url' has deprecation reason 'Use attachment.url instead' (CustomerNeed.url)

feat(schema): [non_breaking] Input field 'CustomerNeedCreateInput.projectId' description changed from 'The project this need is referencing.' to '[INTERNAL] The project this need is referencing.' (CustomerNeedCreateInput.projectId)

feat(schema): [non_breaking] Input field 'CustomerNeedUpdateInput.projectId' description changed from 'The project this need is referencing.' to '[INTERNAL] The project this need is referencing.' (CustomerNeedUpdateInput.projectId)

feat(schema): [non_breaking] Input field 'InheritanceEntityMapping.workflowStates' description changed from 'Mapping of the entity ID to the new entity ID.' to 'Mapping of the WorkflowState ID to the new WorkflowState ID.' (InheritanceEntityMapping.workflowStates)

feat(schema): [non_breaking] Field 'infoSnapshot' was added to object type 'InitiativeUpdate' (InitiativeUpdate.infoSnapshot)

feat(schema): [non_breaking] Field 'isDiffHidden' was added to object type 'InitiativeUpdate' (InitiativeUpdate.isDiffHidden)

feat(schema): [non_breaking] Field 'archivedTeamCount' was added to object type 'ProjectStatusCountPayload' (ProjectStatusCountPayload.archivedTeamCount)

feat(schema): [non_breaking] Field 'privateCount' was added to object type 'ProjectStatusCountPayload' (ProjectStatusCountPayload.privateCount)

feat(schema): [non_breaking] Field 'ProjectStatusCountPayload.count' description changed from 'Number of projects using this project status.' to 'Total number of projects using this project status.' (ProjectStatusCountPayload.count)

feat(schema): [non_breaking] Field 'children' was added to object type 'Team' (Team.children)

feat(schema): [non_breaking] Field 'parent' was added to object type 'Team' (Team.parent)