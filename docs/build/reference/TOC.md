# [C/C++ Building Reference](c-cpp-building-reference.md)
# [Compiling a C/C++ Program](compiling-a-c-cpp-program.md)
## [Setting Compiler Options](setting-compiler-options.md)
### [Compiler Command-Line Syntax](compiler-command-line-syntax.md)
#### [CL Filename Syntax](cl-filename-syntax.md)
#### [Order of CL Options](order-of-cl-options.md)
#### [Return Value of cl.exe](return-value-of-cl-exe.md)
### [CL Environment Variables](cl-environment-variables.md)
### [CL Command Files](cl-command-files.md)
### [Fast Compilation](fast-compilation.md)
### [CL Invokes the Linker](cl-invokes-the-linker.md)
## [Compiler Options](compiler-options.md)
### [Compiler Options Listed by Category](compiler-options-listed-by-category.md)
### [Compiler Options Listed Alphabetically](compiler-options-listed-alphabetically.md)
#### [@ (Specify a Compiler Response File)](at-specify-a-compiler-response-file.md)
#### [-AI (Specify Metadata Directories)](ai-specify-metadata-directories.md)
#### [-analyze (Code Analysis)](analyze-code-analysis.md)
#### [-arch (Minimum CPU Architecture)](arch-minimum-cpu-architecture.md)
##### [-arch (x86)](arch-x86.md)
##### [-arch (x64)](arch-x64.md)
##### [-arch (ARM)](arch-arm.md)
#### [-await (Enable coroutine support)](await-enable-coroutine-support.md)
#### [-bigobj (Increase Number of Sections in .Obj file)](bigobj-increase-number-of-sections-in-dot-obj-file.md)
#### [-C (Preserve Comments During Preprocessing)](c-preserve-comments-during-preprocessing.md)
#### [-c (Compile Without Linking)](c-compile-without-linking.md)
#### [-cgthreads (Code Generation Threads)](cgthreads-code-generation-threads.md)
#### [-clr (Common Language Runtime Compilation)](clr-common-language-runtime-compilation.md)
##### [-clr Restrictions](clr-restrictions.md)
#### [-constexpr (Control constexpr evaluation)](constexpr-control-constexpr-evaluation.md)
#### [-D (Preprocessor Definitions)](d-preprocessor-definitions.md)
#### [-diagnostics (Compiler diagnostics options)](diagnostics-compiler-diagnostic-options.md)
#### [-doc (Process Documentation Comments) (C/C++)](doc-process-documentation-comments-c-cpp.md)
#### [-E (Preprocess to stdout)](e-preprocess-to-stdout.md)
#### [-EH (Exception Handling Model)](eh-exception-handling-model.md)
#### [-EP (Preprocess to stdout Without #line Directives)](ep-preprocess-to-stdout-without-hash-line-directives.md)
#### [-errorReport (Report Internal Compiler Errors)](errorreport-report-internal-compiler-errors.md)
#### [-execution-charset (Set Execution Character Set)](execution-charset-set-execution-character-set.md)
#### [-F (Set Stack Size)](f-set-stack-size.md)
#### [Output-File (-F) Options](output-file-f-options.md)
##### [-FA, -Fa (Listing File)](fa-fa-listing-file.md)
##### [Specifying the Pathname](specifying-the-pathname.md)
##### [-FD (IDE Minimal Rebuild)](fd-ide-minimal-rebuild.md)
##### [-Fd (Program Database File Name)](fd-program-database-file-name.md)
##### [-Fe (Name EXE File)](fe-name-exe-file.md)
##### [-Fi (Preprocess Output File Name)](fi-preprocess-output-file-name.md)
##### [-FI (Name Forced Include File)](fi-name-forced-include-file.md)
##### [-Fm (Name Mapfile)](fm-name-mapfile.md)
##### [-Fo (Object File Name)](fo-object-file-name.md)
##### [-Fp (Name .Pch File)](fp-name-dot-pch-file.md)
##### [-FR, -Fr (Create .Sbr File)](fr-fr-create-dot-sbr-file.md)
##### [-FU (Name Forced #using File)](fu-name-forced-hash-using-file.md)
##### [-Fx (Merge Injected Code)](fx-merge-injected-code.md)
#### [-favor (Optimize for Architecture Specifics)](favor-optimize-for-architecture-specifics.md)
#### [-FC (Full Path of Source Code File in Diagnostics)](fc-full-path-of-source-code-file-in-diagnostics.md)
#### [-fp (Specify Floating-Point Behavior)](fp-specify-floating-point-behavior.md)
#### [-FS (Force Synchronous PDB Writes)](fs-force-synchronous-pdb-writes.md)
#### [-GA (Optimize for Windows Application)](ga-optimize-for-windows-application.md)
#### [-Gd, -Gr, -Gv, -Gz (Calling Convention)](gd-gr-gv-gz-calling-convention.md)
#### [-Ge (Enable Stack Probes)](ge-enable-stack-probes.md)
#### [-GF (Eliminate Duplicate Strings)](gf-eliminate-duplicate-strings.md)
#### [-GH (Enable _pexit Hook Function)](gh-enable-pexit-hook-function.md)
#### [-Gh (Enable _penter Hook Function)](gh-enable-penter-hook-function.md)
#### [-GL (Whole Program Optimization)](gl-whole-program-optimization.md)
#### [-Gm (Enable Minimal Rebuild)](gm-enable-minimal-rebuild.md)
#### [-GR (Enable Run-Time Type Information)](gr-enable-run-time-type-information.md)
#### [-GS (Buffer Security Check)](gs-buffer-security-check.md)
#### [-Gs (Control Stack Checking Calls)](gs-control-stack-checking-calls.md)
#### [-guard (Enable Control Flow Guard)](guard-enable-control-flow-guard.md)
#### [-GT (Support Fiber-Safe Thread-Local Storage)](gt-support-fiber-safe-thread-local-storage.md)
#### [-Gw (Optimize Global Data)](gw-optimize-global-data.md)
#### [-GX (Enable Exception Handling)](gx-enable-exception-handling.md)
#### [-Gy (Enable Function-Level Linking)](gy-enable-function-level-linking.md)
#### [-GZ (Enable Stack Frame Run-Time Error Checking)](gz-enable-stack-frame-run-time-error-checking.md)
#### [-H (Restrict Length of External Names)](h-restrict-length-of-external-names.md)
#### [-HELP (Compiler Command-Line Help)](help-compiler-command-line-help.md)
#### [-homeparams (Copy Register Parameters to Stack)](homeparams-copy-register-parameters-to-stack.md)
#### [-hotpatch (Create Hotpatchable Image)](hotpatch-create-hotpatchable-image.md)
#### [-I (Additional Include Directories)](i-additional-include-directories.md)
#### [-J (Default char Type Is unsigned)](j-default-char-type-is-unsigned.md)
#### [-kernel (Create Kernel Mode Binary)](kernel-create-kernel-mode-binary.md)
#### [-link (Pass Options to Linker)](link-pass-options-to-linker.md)
#### [-LN (Create MSIL Module)](ln-create-msil-module.md)
#### [-MD, -MT, -LD (Use Run-Time Library)](md-mt-ld-use-run-time-library.md)
#### [-MP (Build with Multiple Processes)](mp-build-with-multiple-processes.md)
#### [-nologo (Suppress Startup Banner) (C/C++)](nologo-suppress-startup-banner-c-cpp.md)
#### [-O Options (Optimize Code)](o-options-optimize-code.md)
##### [-O1, -O2 (Minimize Size, Maximize Speed)](o1-o2-minimize-size-maximize-speed.md)
##### [-Ob (Inline Function Expansion)](ob-inline-function-expansion.md)
##### [-Od (Disable (Debug))](od-disable-debug.md)
##### [-Og (Global Optimizations)](og-global-optimizations.md)
##### [-Oi (Generate Intrinsic Functions)](oi-generate-intrinsic-functions.md)
##### [-Os, -Ot (Favor Small Code, Favor Fast Code)](os-ot-favor-small-code-favor-fast-code.md)
##### [-Ox (Enable Most Speed Optimizations)](ox-full-optimization.md)
##### [-Oy (Frame-Pointer Omission)](oy-frame-pointer-omission.md)
#### [-openmp (Enable OpenMP 2.0 Support)](openmp-enable-openmp-2-0-support.md)
#### [-P (Preprocess to a File)](p-preprocess-to-a-file.md)
#### [-permissive- (Standards conformance)](permissive-standards-conformance.md)
#### [-Q Options (Low-Level Operations)](q-options-low-level-operations.md)
##### [-Qfast_transcendentals (Force Fast Transcendentals)](qfast-transcendentals-force-fast-transcendentals.md)
##### [-QIfist (Suppress _ftol)](qifist-suppress-ftol.md)
##### [-Qimprecise_fwaits (Remove fwaits Inside Try Blocks)](qimprecise-fwaits-remove-fwaits-inside-try-blocks.md)
##### [-Qpar (Auto-Parallelizer)](qpar-auto-parallelizer.md)
##### [-Qpar-report (Auto-Parallelizer Reporting Level)](qpar-report-auto-parallelizer-reporting-level.md)
##### [-Qsafe_fp_loads](qsafe-fp-loads.md)
##### [-Qvec-report (Auto-Vectorizer Reporting Level)](qvec-report-auto-vectorizer-reporting-level.md)
#### [-RTC (Run-Time Error Checks)](rtc-run-time-error-checks.md)
#### [-sdl (Enable Additional Security Checks)](sdl-enable-additional-security-checks.md)
#### [-showIncludes (List Include Files)](showincludes-list-include-files.md)
#### [-source-charset (Set Source Character Set)](source-charset-set-source-character-set.md)
#### [-std (Specify Language Standard Version)](std-specify-language-standard-version.md)
#### [-Tc, -Tp, -TC, -TP (Specify Source File Type)](tc-tp-tc-tp-specify-source-file-type.md)
#### [-U, -u (Undefine Symbols)](u-u-undefine-symbols.md)
#### [-utf-8 (Set Source and Executable character sets to UTF-8)](utf-8-set-source-and-executable-character-sets-to-utf-8.md)
#### [-V (Version Number)](v-version-number.md)
#### [-validate-charset (Validate for compatible characters)](validate-charset-validate-for-compatible-characters.md)
#### [-vd (Disable Construction Displacements)](vd-disable-construction-displacements.md)
#### [-vmb, -vmg (Representation Method)](vmb-vmg-representation-method.md)
#### [-vmm, -vms, -vmv (General Purpose Representation)](vmm-vms-vmv-general-purpose-representation.md)
#### [-volatile (volatile Keyword Interpretation)](volatile-volatile-keyword-interpretation.md)
#### [-w, -W0, -W1, -W2, -W3, -W4, -w1, -w2, -w3, -w4, -Wall, -wd, -we, -wo, -Wv, -WX (Warning Level)](compiler-option-warning-level.md)
#### [-WL (Enable One-Line Diagnostics)](wl-enable-one-line-diagnostics.md)
#### [-Wp64 (Detect 64-Bit Portability Issues)](wp64-detect-64-bit-portability-issues.md)
#### [-X (Ignore Standard Include Paths)](x-ignore-standard-include-paths.md)
#### [-Y (Precompiled Headers)](y-precompiled-headers.md)
##### [-Y- (Ignore Precompiled Header Options)](y-ignore-precompiled-header-options.md)
##### [-Yc (Create Precompiled Header File)](yc-create-precompiled-header-file.md)
##### [-Yd (Place Debug Information in Object File)](yd-place-debug-information-in-object-file.md)
##### [-Yl (Inject PCH Reference for Debug Library)](yl-inject-pch-reference-for-debug-library.md)
##### [-Yu (Use Precompiled Header File)](yu-use-precompiled-header-file.md)
#### [-Z7, -Zi, -ZI (Debug Information Format)](z7-zi-zi-debug-information-format.md)
#### [-Za, -Ze (Disable Language Extensions)](za-ze-disable-language-extensions.md)
##### [Microsoft Extensions to C and C++](microsoft-extensions-to-c-and-cpp.md)
#### [-Zc (Conformance)](zc-conformance.md)
##### [-Zc:forScope (Force Conformance in for Loop Scope)](zc-forscope-force-conformance-in-for-loop-scope.md)
##### [-Zc:wchar_t (wchar_t Is Native Type)](zc-wchar-t-wchar-t-is-native-type.md)
##### [-Zc:auto (Deduce Variable Type)](zc-auto-deduce-variable-type.md)
##### [-Zc:trigraphs (Trigraphs Substitution)](zc-trigraphs-trigraphs-substitution.md)
##### [-Zc:rvalueCast (Enforce type conversion rules)](zc-rvaluecast-enforce-type-conversion-rules.md)
##### [-Zc:strictStrings (Disable string literal type conversion)](zc-strictstrings-disable-string-literal-type-conversion.md)
##### [-Zc:inline (Remove unreferenced COMDAT)](zc-inline-remove-unreferenced-comdat.md)
##### [-Zc:implicitNoexcept (Implicit Exception Specifiers)](zc-implicitnoexcept-implicit-exception-specifiers.md)
#### [-Zg (Generate Function Prototypes)](zg-generate-function-prototypes.md)
#### [-Zl (Omit Default Library Name)](zl-omit-default-library-name.md)
#### [-Zm (Specify Precompiled Header Memory Allocation Limit)](zm-specify-precompiled-header-memory-allocation-limit.md)
#### [-Zo (Enhance Optimized Debugging)](zo-enhance-optimized-debugging.md)
#### [-Zp (Struct Member Alignment)](zp-struct-member-alignment.md)
#### [-Zs (Syntax Check Only)](zs-syntax-check-only.md)
#### [-ZW (Windows Runtime Compilation)](zw-windows-runtime-compilation.md)
## [Creating Precompiled Header Files](creating-precompiled-header-files.md)
## [Unicode Support in the Compiler and Linker](unicode-support-in-the-compiler-and-linker.md)
# [Linking](linking.md)
## [Setting Linker Options](setting-linker-options.md)
### [Linker Command-Line Syntax](linker-command-line-syntax.md)
### [LINK Command Files](link-command-files.md)
### [LINK Environment Variables](link-environment-variables.md)
## [Linker Options](linker-options.md)
### [Compiler-Controlled LINK Options](compiler-controlled-link-options.md)
### [LINK Input Files](link-input-files.md)
#### [.Obj Files as Linker Input](dot-obj-files-as-linker-input.md)
#### [.netmodule Files as Linker Input](netmodule-files-as-linker-input.md)
##### [Choosing the Format of .netmodule Input Files](choosing-the-format-of-netmodule-input-files.md)
#### [.Lib Files as Linker Input](dot-lib-files-as-linker-input.md)
#### [.Exp Files as Linker Input](dot-exp-files-as-linker-input.md)
#### [.Def Files as Linker Input](dot-def-files-as-linker-input.md)
#### [.Pdb Files as Linker Input](dot-pdb-files-as-linker-input.md)
#### [.Res Files as Linker Input](dot-res-files-as-linker-input.md)
#### [.Exe Files as Linker Input](dot-exe-files-as-linker-input.md)
#### [.Txt Files as Linker Input](dot-txt-files-as-linker-input.md)
#### [.Ilk Files as Linker Input](dot-ilk-files-as-linker-input.md)
### [LINK Output](link-output.md)
### [Reserved Words](reserved-words.md)
### [@ (Specify a Linker Response File)](at-specify-a-linker-response-file.md)
### [-ALIGN (Section Alignment)](align-section-alignment.md)
### [-ALLOWBIND (Prevent DLL Binding)](allowbind-prevent-dll-binding.md)
### [-ALLOWISOLATION (Manifest Lookup)](allowisolation-manifest-lookup.md)
### [-APPCONTAINER (Windows Store App)](appcontainer-windows-store-app.md)
### [-ASSEMBLYDEBUG (Add DebuggableAttribute)](assemblydebug-add-debuggableattribute.md)
### [-ASSEMBLYLINKRESOURCE (Link to .NET Framework Resource)](assemblylinkresource-link-to-dotnet-framework-resource.md)
### [-ASSEMBLYMODULE (Add a MSIL Module to the Assembly)](assemblymodule-add-a-msil-module-to-the-assembly.md)
### [-ASSEMBLYRESOURCE (Embed a Managed Resource)](assemblyresource-embed-a-managed-resource.md)
### [-BASE (Base Address)](base-base-address.md)
### [-CGTHREADS (Compiler Threads)](cgthreads-compiler-threads.md)
### [-CLRIMAGETYPE (Specify Type of CLR Image)](clrimagetype-specify-type-of-clr-image.md)
### [-CLRSUPPORTLASTERROR (Preserve Last Error Code for PInvoke Calls)](clrsupportlasterror-preserve-last-error-code-for-pinvoke-calls.md)
### [-CLRTHREADATTRIBUTE (Set CLR Thread Attribute)](clrthreadattribute-set-clr-thread-attribute.md)
### [-CLRUNMANAGEDCODECHECK (Add SupressUnmanagedCodeSecurityAttribute)](clrunmanagedcodecheck-add-supressunmanagedcodesecurityattribute.md)
### [-DEBUG (Generate Debug Info)](debug-generate-debug-info.md)
### [-DEBUGTYPE (Debug Info Options)](debugtype-debug-info-options.md)
### [-DEF (Specify Module-Definition File)](def-specify-module-definition-file.md)
### [-DEFAULTLIB (Specify Default Library)](defaultlib-specify-default-library.md)
### [-DELAY (Delay Load Import Settings)](delay-delay-load-import-settings.md)
### [-DELAYLOAD (Delay Load Import)](delayload-delay-load-import.md)
### [-DELAYSIGN (Partially Sign an Assembly)](delaysign-partially-sign-an-assembly.md)
### [-DLL (Build a DLL)](dll-build-a-dll.md)
### [-DRIVER (Windows NT Kernel Mode Driver)](driver-windows-nt-kernel-mode-driver.md)
### [-DYNAMICBASE (Use address space layout randomization)](dynamicbase-use-address-space-layout-randomization.md)
### [-ENTRY (Entry-Point Symbol)](entry-entry-point-symbol.md)
### [-ERRORREPORT (Report Internal Linker Errors)](errorreport-report-internal-linker-errors.md)
### [-EXPORT (Exports a Function)](export-exports-a-function.md)
### [-FIXED (Fixed Base Address)](fixed-fixed-base-address.md)
### [-FORCE (Force File Output)](force-force-file-output.md)
### [-FUNCTIONPADMIN (Create Hotpatchable Image)](functionpadmin-create-hotpatchable-image.md)
### [-GENPROFILE, -FASTGENPROFILE (Generate Profiling Instrumented Build)](genprofile-fastgenprofile-generate-profiling-instrumented-build.md)
### [-GUARD (Enable Guard Checks)](guard-enable-guard-checks.md)
### [-HEAP (Set Heap Size)](heap-set-heap-size.md)
### [-HIGHENTROPYVA (Support 64-Bit ASLR)](highentropyva-support-64-bit-aslr.md)
### [-IDLOUT (Name MIDL Output Files)](idlout-name-midl-output-files.md)
### [-IGNORE (Ignore Specific Warnings)](ignore-ignore-specific-warnings.md)
### [-IGNOREIDL (Don't Process Attributes into MIDL)](ignoreidl-don-t-process-attributes-into-midl.md)
### [-IMPLIB (Name Import Library)](implib-name-import-library.md)
### [-INCLUDE (Force Symbol References)](include-force-symbol-references.md)
### [-INCREMENTAL (Link Incrementally)](incremental-link-incrementally.md)
### [-INTEGRITYCHECK (Require Signature Check)](integritycheck-require-signature-check.md)
### [-KEYCONTAINER (Specify a Key Container to Sign an Assembly)](keycontainer-specify-a-key-container-to-sign-an-assembly.md)
### [-KEYFILE (Specify Key or Key Pair to Sign an Assembly)](keyfile-specify-key-or-key-pair-to-sign-an-assembly.md)
### [-LARGEADDRESSAWARE (Handle Large Addresses)](largeaddressaware-handle-large-addresses.md)
### [-LIBPATH (Additional Libpath)](libpath-additional-libpath.md)
### [-LTCG (Link-time Code Generation)](ltcg-link-time-code-generation.md)
### [-MACHINE (Specify Target Platform)](machine-specify-target-platform.md)
### [-MANIFEST (Create Side-by-Side Assembly Manifest)](manifest-create-side-by-side-assembly-manifest.md)
### [-MANIFESTDEPENDENCY (Specify Manifest Dependencies)](manifestdependency-specify-manifest-dependencies.md)
### [-MANIFESTFILE (Name Manifest File)](manifestfile-name-manifest-file.md)
### [-MANIFESTINPUT (Specify Manifest Input)](manifestinput-specify-manifest-input.md)
### [-MANIFESTUAC (Embeds UAC information in manifest)](manifestuac-embeds-uac-information-in-manifest.md)
### [-MAP (Generate Mapfile)](map-generate-mapfile.md)
### [-MAPINFO (Include Information in Mapfile)](mapinfo-include-information-in-mapfile.md)
### [-MERGE (Combine Sections)](merge-combine-sections.md)
### [-MIDL (Specify MIDL Command Line Options)](midl-specify-midl-command-line-options.md)
### [-NATVIS (Add Natvis to PDB)](natvis-add-natvis-to-pdb.md)
### [-NOASSEMBLY (Create a MSIL Module)](noassembly-create-a-msil-module.md)
### [-NODEFAULTLIB (Ignore Libraries)](nodefaultlib-ignore-libraries.md)
### [-NOENTRY (No Entry Point)](noentry-no-entry-point.md)
### [-NOLOGO (Suppress Startup Banner) (Linker)](nologo-suppress-startup-banner-linker.md)
### [-NXCOMPAT (Compatible with Data Execution Prevention)](nxcompat-compatible-with-data-execution-prevention.md)
### [-OPT (Optimizations)](opt-optimizations.md)
### [-ORDER (Put Functions in Order)](order-put-functions-in-order.md)
### [-OUT (Output File Name)](out-output-file-name.md)
### [-PDB (Use Program Database)](pdb-use-program-database.md)
### [-PDBALTPATH (Use Alternate PDB Path)](pdbaltpath-use-alternate-pdb-path.md)
### [-PDBSTRIPPED (Strip Private Symbols)](pdbstripped-strip-private-symbols.md)
### [-PGD (Specify Database for Profile-Guided Optimizations)](pgd-specify-database-for-profile-guided-optimizations.md)
### [-PROFILE (Performance Tools Profiler)](profile-performance-tools-profiler.md)
### [-RELEASE (Set the Checksum)](release-set-the-checksum.md)
### [-SAFESEH (Image has Safe Exception Handlers)](safeseh-image-has-safe-exception-handlers.md)
### [-SECTION (Specify Section Attributes)](section-specify-section-attributes.md)
### [-STACK (Stack Allocations)](stack-stack-allocations.md)
### [-STUB (MS-DOS Stub File Name)](stub-ms-dos-stub-file-name.md)
### [-SUBSYSTEM (Specify Subsystem)](subsystem-specify-subsystem.md)
### [-SWAPRUN (Load Linker Output to Swap File)](swaprun-load-linker-output-to-swap-file.md)
### [-TLBID (Specify Resource ID for TypeLib)](tlbid-specify-resource-id-for-typelib.md)
### [-TLBOUT (Name .TLB File)](tlbout-name-dot-tlb-file.md)
### [-TSAWARE (Create Terminal Server Aware Application)](tsaware-create-terminal-server-aware-application.md)
### [-VERBOSE (Print Progress Messages)](verbose-print-progress-messages.md)
### [-VERSION (Version Information)](version-version-information.md)
### [-WHOLEARCHIVE (Include All Library Object Files)](wholearchive-include-all-library-object-files.md)
### [-WINMD (Generate Windows Metadata)](winmd-generate-windows-metadata.md)
### [-WINMDFILE (Specify winmd File)](winmdfile-specify-winmd-file.md)
### [-WINMDKEYFILE (Specify winmd Key File)](winmdkeyfile-specify-winmd-key-file.md)
### [-WINMDKEYCONTAINER (Specify Key Container)](winmdkeycontainer-specify-key-container.md)
### [-WINMDDELAYSIGN (Partially Sign a winmd)](winmddelaysign-partially-sign-a-winmd.md)
### [-WX (Treat Linker Warnings as Errors)](wx-treat-linker-warnings-as-errors.md)
## [Module-Definition (.Def) Files](module-definition-dot-def-files.md)
### [Rules for Module-Definition Statements](rules-for-module-definition-statements.md)
#### [EXPORTS](exports.md)
#### [LIBRARY](library.md)
#### [HEAPSIZE](heapsize.md)
#### [NAME (C/C++)](name-c-cpp.md)
#### [SECTIONS (C/C++)](sections-c-cpp.md)
#### [STACKSIZE](stacksize.md)
#### [STUB](stub.md)
#### [VERSION (C/C++)](version-c-cpp.md)
## [Linker Support for Delay-Loaded DLLs](linker-support-for-delay-loaded-dlls.md)
### [Specifying DLLs to Delay Load](specifying-dlls-to-delay-load.md)
### [Explicitly Unloading a Delay-Loaded DLL](explicitly-unloading-a-delay-loaded-dll.md)
### [Binding Imports](binding-imports.md)
### [Loading All Imports for a Delay-Loaded DLL](loading-all-imports-for-a-delay-loaded-dll.md)
### [Error Handling and Notification](error-handling-and-notification.md)
#### [Notification Hooks](notification-hooks.md)
#### [Failure Hooks](failure-hooks.md)
#### [Exceptions (C/C++)](exceptions-c-cpp.md)
### [Dumping Delay-Loaded Imports](dumping-delay-loaded-imports.md)
### [Constraints of Delay Loading DLLs](constraints-of-delay-loading-dlls.md)
### [Understanding the Helper Function](understanding-the-helper-function.md)
#### [Changes in the DLL Delayed Loading Helper Function Since Visual C++ 6.0](changes-in-the-dll-delayed-loading-helper-function-since-visual-cpp-6-0.md)
#### [Calling Conventions, Parameters, and Return Type](calling-conventions-parameters-and-return-type.md)
#### [Structure and Constant Definitions](structure-and-constant-definitions.md)
#### [Calculating Necessary Values](calculating-necessary-values.md)
#### [Unloading a Delay-Loaded DLL](unloading-a-delay-loaded-dll.md)
### [Developing Your Own Helper Function](developing-your-own-helper-function.md)
# [Release Builds](release-builds.md)
## [How to: Create a Release Build](how-to-create-a-release-build.md)
## [Common Problems When Creating a Release Build](common-problems-when-creating-a-release-build.md)
## [Fixing Release Build Problems](fixing-release-build-problems.md)
### [Using VERIFY Instead of ASSERT](using-verify-instead-of-assert.md)
### [Using the Debug Build to Check for Memory Overwrite](using-the-debug-build-to-check-for-memory-overwrite.md)
### [How to: Debug a Release Build](how-to-debug-a-release-build.md)
### [Checking for Memory Overwrites](checking-for-memory-overwrites.md)
# [Optimizing Your Code](optimizing-your-code.md)
## [Optimization Pragmas and Keywords](optimization-pragmas-and-keywords.md)
## [Improving Compiler Throughput](improving-compiler-throughput.md)
## [Why Floating-Point Numbers May Lose Precision](why-floating-point-numbers-may-lose-precision.md)
### [IEEE Floating-Point Representation](ieee-floating-point-representation.md)
## [Tips for Improving Time-Critical Code](tips-for-improving-time-critical-code.md)
## [Using Function Name Without () Produces No Code](using-function-name-without-parens-produces-no-code.md)
## [Optimization Best Practices](optimization-best-practices.md)
# [C/C++ Build Tools](c-cpp-build-tools.md)
## [BSCMAKE Reference](bscmake-reference.md)
### [Building Browse Information Files: Overview](building-browse-information-files-overview.md)
### [Building a .Bsc File](building-a-dot-bsc-file.md)
#### [Creating an .Sbr File](creating-an-dot-sbr-file.md)
#### [How BSCMAKE Builds a .Bsc File](how-bscmake-builds-a-dot-bsc-file.md)
### [BSCMAKE Command Line](bscmake-command-line.md)
### [BSCMAKE Command File (Response File)](bscmake-command-file-response-file.md)
### [BSCMAKE Options](bscmake-options.md)
### [BSCMAKE Exit Codes](bscmake-exit-codes.md)
## [LIB Reference](lib-reference.md)
### [Overview of LIB](overview-of-lib.md)
#### [How to: Set LIB.EXE Options in the Visual Studio Development Environment](how-to-set-lib-exe-options-in-the-visual-studio-development-environment.md)
#### [LIB Input Files](lib-input-files.md)
#### [LIB Output Files](lib-output-files.md)
#### [Other LIB Output](other-lib-output.md)
#### [Structure of a Library](structure-of-a-library.md)
### [Running LIB](running-lib.md)
### [Managing a Library](managing-a-library.md)
### [Extracting a Library Member](extracting-a-library-member.md)
### [Working with Import Libraries and Export Files](working-with-import-libraries-and-export-files.md)
#### [Building an Import Library and Export File](building-an-import-library-and-export-file.md)
#### [Using an Import Library and Export File](using-an-import-library-and-export-file.md)
## [EDITBIN Reference](editbin-reference.md)
### [EDITBIN Command Line](editbin-command-line.md)
### [EDITBIN Options](editbin-options.md)
#### [-ALLOWISOLATION](allowisolation.md)
#### [-ALLOWBIND](allowbind.md)
#### [-APPCONTAINER](appcontainer.md)
#### [-BIND](bind.md)
#### [-DYNAMICBASE](dynamicbase.md)
#### [-ERRORREPORT (editbin.exe)](errorreport-editbin-exe.md)
#### [-HEAP](heap.md)
#### [-HIGHENTROPYVA](highentropyva.md)
#### [-INTEGRITYCHECK](integritycheck.md)
#### [-LARGEADDRESSAWARE](largeaddressaware.md)
#### [-NOLOGO (EDITBIN)](nologo-editbin.md)
#### [-NXCOMPAT](nxcompat.md)
#### [-REBASE](rebase.md)
#### [-RELEASE](release.md)
#### [-SECTION (EDITBIN)](section-editbin.md)
#### [-STACK](stack.md)
#### [-SUBSYSTEM](subsystem.md)
#### [-SWAPRUN](swaprun.md)
#### [-TSAWARE](tsaware.md)
#### [-VERSION](version.md)
## [DUMPBIN Reference](dumpbin-reference.md)
### [DUMPBIN Command Line](dumpbin-command-line.md)
### [DUMPBIN Options](dumpbin-options.md)
#### [-ALL](all.md)
#### [-ARCHIVEMEMBERS](archivemembers.md)
#### [-CLRHEADER](clrheader.md)
#### [-DEPENDENTS](dependents.md)
#### [-DIRECTIVES](directives.md)
#### [-DISASM](disasm.md)
#### [-ERRORREPORT (dumpbin.exe)](errorreport-dumpbin-exe.md)
#### [-EXPORTS](dash-exports.md)
#### [-FPO](fpo.md)
#### [-HEADERS](headers.md)
#### [-IMPORTS (DUMPBIN)](imports-dumpbin.md)
#### [-LINENUMBERS](linenumbers.md)
#### [-LINKERMEMBER](linkermember.md)
#### [-LOADCONFIG](loadconfig.md)
#### [-OUT (DUMPBIN)](out-dumpbin.md)
#### [-PDATA](pdata.md)
#### [-PDBPATH](pdbpath.md)
#### [-RANGE](range.md)
#### [-RAWDATA](rawdata.md)
#### [-RELOCATIONS](relocations.md)
#### [-SECTION (DUMPBIN)](section-dumpbin.md)
#### [-SUMMARY](summary.md)
#### [-SYMBOLS](symbols.md)
#### [-TLS](tls.md)
## [ERRLOOK Reference](errlook-reference.md)
### [Value Edit Control](value-edit-control.md)
### [Error Message Edit Control](error-message-edit-control.md)
### [Modules Button](modules-button.md)
### [Look Up Button](look-up-button.md)
## [Decorated Names](decorated-names.md)
## [Profile-Guided Optimizations](profile-guided-optimizations.md)
### [Profile Guided Optimization in the Performance and Diagnostics Hub](profile-guided-optimization-in-the-performance-and-diagnostics-hub.md)
### [Tools for Manual Profile-Guided Optimization](tools-for-manual-profile-guided-optimization.md)
#### [Environment Variables for Profile-Guided Optimizations](environment-variables-for-profile-guided-optimizations.md)
##### [PogoSafeMode](pogosafemode.md)
##### [VCPROFILE_ALLOC_SCALE](vcprofile-alloc-scale.md)
##### [VCPROFILE_PATH](vcprofile-path.md)
#### [pgomgr](pgomgr.md)
#### [pgosweep](pgosweep.md)
### [How to: Merge Multiple PGO Profiles into a Single Profile](how-to-merge-multiple-pgo-profiles-into-a-single-profile.md)
# [Compiler Errors C999 to C2499](../../error-messages/compiler-errors-1/TOC.md)
# [Compiler Errors C2500 to C3999](../../error-messages/compiler-errors-2/TOC.md)
# [Compiler Warnings](../../error-messages/compiler-warnings/TOC.md)
# [Tool Errors](../../error-messages/tool-errors/TOC.md)