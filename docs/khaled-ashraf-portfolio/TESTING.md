# Testing and validation

## Preparation checks completed

- Captured source at the recorded commit.
- Checked archive paths, symlinks, and file inclusion rules.
- Replaced detected credential literals, connection strings, and contact addresses with placeholders.
- Removed data exports, runtime environments, private keys, generated output, and internal assistant artifacts.
- Re-scanned the prepared text for the supported sensitive-value patterns.
- Parsed generated JSON documents and package manifests.

## Application validation

Dependencies were not installed. Application tests, servers, migrations, seeders, and database or external-service requests were not run. Runtime correctness after configuration and data removal remains to be verified by the project maintainer.

## Existing test sources

- `backend/analytics/tests/test_access.py`
- `backend/analytics/tests/test_arm_identity.py`
- `backend/analytics/tests/test_arm_lms.py`
- `backend/analytics/tests/test_attendance.py`
- `backend/analytics/tests/test_attendance_matrices.py`
- `backend/analytics/tests/test_attendance_reconciliation.py`
- `backend/analytics/tests/test_course_display.py`
- `backend/analytics/tests/test_database_isolation.py`
- `backend/analytics/tests/test_database_transfer.py`
- `backend/analytics/tests/test_directory_attendance.py`
- `backend/analytics/tests/test_graph_timing.py`
- `backend/analytics/tests/test_identity_management.py`
- `backend/analytics/tests/test_identity_restoration_access.py`
- `backend/analytics/tests/test_import.py`
- `backend/analytics/tests/test_learner_directory_export.py`
- `backend/analytics/tests/test_lecture_library.py`
- `backend/analytics/tests/test_lecture_library_sync.py`
- `backend/analytics/tests/test_lecture_timing.py`
- `backend/analytics/tests/test_library_merge_resolution.py`
- `backend/analytics/tests/test_master_export.py`
- `backend/analytics/tests/test_metrics_api.py`
- `backend/analytics/tests/test_module_performance.py`
- `backend/analytics/tests/test_provision_owner.py`
- `backend/analytics/tests/test_real_workbook.py`
- `backend/analytics/tests/test_recording_selection.py`
- `backend/analytics/tests/test_teams_discovery.py`
- `backend/analytics/tests/test_transcript_selection.py`
- `backend/config/test_settings.py`
- `frontend/tests/attendance-hours.test.ts`
- `frontend/tests/learner-directory.test.ts`
- `frontend/tests/learner-table-scroll.test.ts`
- `frontend/tests/module-performance.test.ts`
