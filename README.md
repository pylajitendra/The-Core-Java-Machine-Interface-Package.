# The-Core-Java-Machine-Interface-Package.

**Description:**

The Machine Interface Package with Core Java.

package org.smeup.sys.mi.core;

import org.eclipse.emf.ecore.EClass;
import org.eclipse.emf.ecore.EDataType;
import org.eclipse.emf.ecore.EPackage;

/**
 * <!-- begin-user-doc -->
 * The <b>Package</b> for the model.
 * It contains accessors for the meta objects to represent
 * <ul>
 *   <li>each class,</li>
 *   <li>each feature of each class,</li>
 *   <li>each enum,</li>
 *   <li>and each data type</li>
 * </ul>
 * <!-- end-user-doc -->
 */
public interface QMachineInterfaceCorePackage extends EPackage {
	/**
	 * The package name.
	 * <!-- begin-user-doc -->
	 * <!-- end-user-doc -->
	 * @generated
	 */
	String eNAME = "core";

	/**
	 * The package namespace URI.
	 * <!-- begin-user-doc -->
	 * <!-- end-user-doc -->
	 * @generated
	 */
	String eNS_URI = "http://www.smeup.org/asup";

	/**
	 * The package namespace name.
	 * <!-- begin-user-doc -->
	 * <!-- end-user-doc -->
	 * @generated
	 */
	String eNS_PREFIX = "mi-core";

	/**
	 * The singleton instance of the package.
	 * <!-- begin-user-doc -->
	 * <!-- end-user-doc -->
	 * @generated
	 */
	QMachineInterfaceCorePackage eINSTANCE = org.smeup.sys.mi.core.impl.MachineInterfaceCorePackageImpl.init();

	/**
	 * The meta object id for the '{@link java.nio.ByteBuffer <em>Java Byte Buffer</em>}' class.
	 * <!-- begin-user-doc -->
	 * <!-- end-user-doc -->
	 * @see java.nio.ByteBuffer
	 * @see org.smeup.sys.mi.core.impl.MachineInterfaceCorePackageImpl#getJavaByteBuffer()
	 * @generated
	 */
	int JAVA_BYTE_BUFFER = 0;

	/**
	 * The number of structural features of the '<em>Java Byte Buffer</em>' class.
	 * <!-- begin-user-doc -->
	 * <!-- end-user-doc -->
	 * @generated
	 * @ordered
	 */
	int JAVA_BYTE_BUFFER_FEATURE_COUNT = 0;

	/**
	 * The meta object id for the '{@link java.util.concurrent.BlockingQueue<E> <em>Java Blocking Queue</em>}' class.
	 * <!-- begin-user-doc -->
	 * <!-- end-user-doc -->
	 * @see java.util.concurrent.BlockingQueue<E>
	 * @see org.smeup.sys.mi.core.impl.MachineInterfaceCorePackageImpl#getJavaBlockingQueue()
	 * @generated
	 */
	int JAVA_BLOCKING_QUEUE = 1;

	/**
	 * The number of structural features of the '<em>Java Blocking Queue</em>' class.
	 * <!-- begin-user-doc -->
	 * <!-- end-user-doc -->
	 * @generated
	 * @ordered
	 */
	int JAVA_BLOCKING_QUEUE_FEATURE_COUNT = 0;

	/**
	 * The meta object id for the '{@link java.util.concurrent.Callable <em>Java Callable</em>}' class.
	 * <!-- begin-user-doc -->
	 * <!-- end-user-doc -->
	 * @see java.util.concurrent.Callable
	 * @see org.smeup.sys.mi.core.impl.MachineInterfaceCorePackageImpl#getJavaCallable()
	 * @generated
	 */
	int JAVA_CALLABLE = 2;

	/**
	 * The number of structural features of the '<em>Java Callable</em>' class.
	 * <!-- begin-user-doc -->
	 * <!-- end-user-doc -->
	 * @generated
	 * @ordered
	 */
	int JAVA_CALLABLE_FEATURE_COUNT = 0;

	/**
	 * The meta object id for the '{@link java.nio.charset.Charset <em>Java Charset</em>}' class.
	 * <!-- begin-user-doc -->
	 * <!-- end-user-doc -->
	 * @see java.nio.charset.Charset
	 * @see org.smeup.sys.mi.core.impl.MachineInterfaceCorePackageImpl#getJavaCharset()
	 * @generated
	 */
	int JAVA_CHARSET = 3;

	/**
	 * The number of structural features of the '<em>Java Charset</em>' class.
	 * <!-- begin-user-doc -->
	 * <!-- end-user-doc -->
	 * @generated
	 * @ordered
	 */
	int JAVA_CHARSET_FEATURE_COUNT = 0;

	/**
	 * The meta object id for the '{@link java.io.Closeable <em>Java Closeable</em>}' class.
	 * <!-- begin-user-doc -->
	 * <!-- end-user-doc -->
	 * @see java.io.Closeable
	 * @see org.smeup.sys.mi.core.impl.MachineInterfaceCorePackageImpl#getJavaCloseable()
	 * @generated
	 */
	int JAVA_CLOSEABLE = 4;

	/**
	 * The number of structural features of the '<em>Java Closeable</em>' class.
	 * <!-- begin-user-doc -->
	 * <!-- end-user-doc -->
	 * @generated
	 * @ordered
	 */
	int JAVA_CLOSEABLE_FEATURE_COUNT = 0;

	/**
	 * The meta object id for the '{@link java.util.concurrent.ConcurrentMap<K, V> <em>Java Concurrent Map</em>}' class.
	 * <!-- begin-user-doc -->
	 * <!-- end-user-doc -->
	 * @see java.util.concurrent.ConcurrentMap<K, V>
	 * @see org.smeup.sys.mi.core.impl.MachineInterfaceCorePackageImpl#getJavaConcurrentMap()
	 * @generated
	 */
	int JAVA_CONCURRENT_MAP = 5;

	/**
	 * The number of structural features of the '<em>Java Concurrent Map</em>' class.
	 * <!-- begin-user-doc -->
	 * <!-- end-user-doc -->
	 * @generated
	 * @ordered
	 */
	int JAVA_CONCURRENT_MAP_FEATURE_COUNT = 0;

	/**
	 * The meta object id for the '{@link java.util.concurrent.ExecutorService <em>Java Executor Service</em>}' class.
	 * <!-- begin-user-doc -->
	 * <!-- end-user-doc -->
	 * @see java.util.concurrent.ExecutorService
	 * @see org.smeup.sys.mi.core.impl.MachineInterfaceCorePackageImpl#getJavaExecutorService()
	 * @generated
	 */
	int JAVA_EXECUTOR_SERVICE = 7;

	/**
	 * The meta object id for the '{@link java.lang.Enum<E> <em>Java Enum</em>}' class.
	 * <!-- begin-user-doc -->
	 * <!-- end-user-doc -->
	 * @see java.lang.Enum<E>
	 * @see org.smeup.sys.mi.core.impl.MachineInterfaceCorePackageImpl#getJavaEnum()
	 * @generated
	 */
	int JAVA_ENUM = 6;

	/**
	 * The number of structural features of the '<em>Java Enum</em>' class.
	 * <!-- begin-user-doc -->
	 * <!-- end-user-doc -->
	 * @generated
	 * @ordered
	 */
	int JAVA_ENUM_FEATURE_COUNT = 0;

	/**
	 * The number of structural features of the '<em>Java Executor Service</em>' class.
	 * <!-- begin-user-doc -->
	 * <!-- end-user-doc -->
	 * @generated
	 * @ordered
	 */
	int JAVA_EXECUTOR_SERVICE_FEATURE_COUNT = 0;

	/**
	 * The meta object id for the '{@link java.util.Iterator <em>Java Iterator</em>}' class.
	 * <!-- begin-user-doc -->
	 * <!-- end-user-doc -->
	 * @see java.util.Iterator
	 * @see org.smeup.sys.mi.core.impl.MachineInterfaceCorePackageImpl#getJavaIterator()
	 * @generated
	 */
	int JAVA_ITERATOR = 9;

	/**
	 * The meta object id for the '{@link java.util.List <em>Java List</em>}' class.
	 * <!-- begin-user-doc -->
	 * <!-- end-user-doc -->
	 * @see java.util.List
	 * @see org.smeup.sys.mi.core.impl.MachineInterfaceCorePackageImpl#getJavaList()
	 * @generated
	 */
	int JAVA_LIST = 10;

	/**
	 * The meta object id for the '{@link java.lang.Number <em>Java Number</em>}' class.
	 * <!-- begin-user-doc -->
	 * <!-- end-user-doc -->
	 * @see java.lang.Number
	 * @see org.smeup.sys.mi.core.impl.MachineInterfaceCorePackageImpl#getJavaNumber()
	 * @generated
	 */
	int JAVA_NUMBER = 11;

	/**
	 * The meta object id for the '{@link java.security.Principal <em>Java Principal</em>}' class.
	 * <!-- begin-user-doc -->
	 * <!-- end-user-doc -->
	 * @see java.security.Principal
	 * @see org.smeup.sys.mi.core.impl.MachineInterfaceCorePackageImpl#getJavaPrincipal()
	 * @generated
	 */
	int JAVA_PRINCIPAL = 12;

	/**
	 * The meta object id for the '{@link java.lang.Thread <em>Java Thread</em>}' class.
	 * <!-- begin-user-doc -->
	 * <!-- end-user-doc -->
	 * @see java.lang.Thread
	 * @see org.smeup.sys.mi.core.impl.MachineInterfaceCorePackageImpl#getJavaThread()
	 * @generated
	 */
	int JAVA_THREAD = 14;

	/**
	 * The meta object id for the '{@link java.lang.ThreadGroup <em>Java Thread Group</em>}' class.
	 * <!-- begin-user-doc -->
	 * <!-- end-user-doc -->
	 * @see java.lang.ThreadGroup
	 * @see org.smeup.sys.mi.core.impl.MachineInterfaceCorePackageImpl#getJavaThreadGroup()
	 * @generated
	 */
	int JAVA_THREAD_GROUP = 15;

	/**
	 * The meta object id for the '{@link java.lang.management.ThreadInfo <em>Java Thread Info</em>}' class.
	 * <!-- begin-user-doc -->
	 * <!-- end-user-doc -->
	 * @see java.lang.management.ThreadInfo
	 * @see org.smeup.sys.mi.core.impl.MachineInterfaceCorePackageImpl#getJavaThreadInfo()
	 * @generated
	 */
	int JAVA_THREAD_INFO = 16;

	/**
	 * The meta object id for the '<em>Java Annotation</em>' data type.
	 * <!-- begin-user-doc -->
	 * <!-- end-user-doc -->
	 * @see java.lang.annotation.Annotation
	 * @see org.smeup.sys.mi.core.impl.MachineInterfaceCorePackageImpl#getJavaAnnotation()
	 * @generated
	 */
	int JAVA_ANNOTATION = 17;

	/**
	 * The meta object id for the '<em>Java Dictionary</em>' data type.
	 * <!-- begin-user-doc -->
	 * <!-- end-user-doc -->
	 * @see java.util.Dictionary
	 * @see org.smeup.sys.mi.core.impl.MachineInterfaceCorePackageImpl#getJavaDictionary()
	 * @generated
	 */
	int JAVA_DICTIONARY = 18;

	/**
	 * The meta object id for the '<em>Java Exception</em>' data type.
	 * <!-- begin-user-doc -->
	 * <!-- end-user-doc -->
	 * @see java.lang.Exception
	 * @see org.smeup.sys.mi.core.impl.MachineInterfaceCorePackageImpl#getJavaException()
	 * @generated
	 */
	int JAVA_EXCEPTION = 19;

	/**
	 * The meta object id for the '<em>Java Input Stream</em>' data type.
	 * <!-- begin-user-doc -->
	 * <!-- end-user-doc -->
	 * @see java.io.InputStream
	 * @see org.smeup.sys.mi.core.impl.MachineInterfaceCorePackageImpl#getJavaInputStream()
	 * @generated
	 */
	int JAVA_INPUT_STREAM = 20;

	/**
	 * The meta object id for the '<em>Java IO Exception</em>' data type.
	 * <!-- begin-user-doc -->
	 * <!-- end-user-doc -->
	 * @see java.io.IOException
	 * @generated
	 */
	int JAVA_IO_EXCEPTION = 21;

	/**
	 * The meta object id for the '{@link java.lang.Iterable <em>Java Iterable</em>}' class.
	 * <!-- begin-user-doc -->
	 * <!-- end-user-doc -->
	 * @see java.lang.Iterable
	 * @see org.smeup.sys.mi.core.impl.MachineInterfaceCorePackageImpl#getJavaIterable()
	 * @generated
	 */
	int JAVA_ITERABLE = 8;

	/**
	 * The number of structural features of the '<em>Java Iterable</em>' class.
	 * <!-- begin-user-doc -->
	 * <!-- end-user-doc -->
	 * @generated
	 * @ordered
	 */
	int JAVA_ITERABLE_FEATURE_COUNT = 0;

	/**
	 * The number of structural features of the '<em>Java Iterator</em>' class.
	 * <!-- begin-user-doc -->
	 * <!-- end-user-doc -->
	 * @generated
	 * @ordered
	 */
	int JAVA_ITERATOR_FEATURE_COUNT = 0;

	/**
	 * The number of structural features of the '<em>Java List</em>' class.
	 * <!-- begin-user-doc -->
	 * <!-- end-user-doc -->
	 * @generated
	 * @ordered
	 */
	int JAVA_LIST_FEATURE_COUNT = 0;

	/**
	 * The number of structural features of the '<em>Java Number</em>' class.
	 * <!-- begin-user-doc -->
	 * <!-- end-user-doc -->
	 * @generated
	 * @ordered
	 */
	int JAVA_NUMBER_FEATURE_COUNT = 0;

	/**
	 * The number of structural features of the '<em>Java Principal</em>' class.
	 * <!-- begin-user-doc -->
	 * <!-- end-user-doc -->
	 * @generated
	 * @ordered
	 */
	int JAVA_PRINCIPAL_FEATURE_COUNT = 0;

	/**
	 * The meta object id for the '<em>Java Map</em>' data type.
	 * <!-- begin-user-doc -->
	 * <!-- end-user-doc -->
	 * @see java.util.Map
	 * @see org.smeup.sys.mi.core.impl.MachineInterfaceCorePackageImpl#getJavaMap()
	 * @generated
	 */
	int JAVA_MAP = 22;

	/**
	 * The meta object id for the '<em>Java Output Stream</em>' data type.
	 * <!-- begin-user-doc -->
	 * <!-- end-user-doc -->
	 * @see java.io.OutputStream
	 * @see org.smeup.sys.mi.core.impl.MachineInterfaceCorePackageImpl#getJavaOutputStream()
	 * @generated
	 */
	int JAVA_OUTPUT_STREAM = 23;

	/**
	 * The meta object id for the '<em>Java Properties</em>' data type.
	 * <!-- begin-user-doc -->
	 * <!-- end-user-doc -->
	 * @see java.util.Properties
	 * @generated
	 */
	int JAVA_PROPERTIES = 24;

	/**
	 * The meta object id for the '{@link java.lang.Runnable <em>Java Runnable</em>}' class.
	 * <!-- begin-user-doc -->
	 * <!-- end-user-doc -->
	 * @see java.lang.Runnable
	 * @generated
	 */
